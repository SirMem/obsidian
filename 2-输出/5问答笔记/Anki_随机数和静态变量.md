---
due: 2023-10-15
title: Anki_随机数和静态变量
tags:
  - C语言
  - Anki
cards-deck: 2-输出::5问答笔记
---

#card


## 摘录挖空区
### rand()
ANSI C库提供了rand()函数生成==随机数==。实际上，rand()是“==伪随机数生成器==”，意思是可预测生成数字的实际序列。但是，数字在其取值范围内均匀分布。
^1697351050635
可移植版本的方案开始于一个“种子”数字。该函数使用该种子生成新的~~*数*~~==，这个新数又成为新的种子==。然后，新种子可用于生成==更新的种子==，以此类推，而这个种子即是rand()函数里面的==srand()==。而种子需要是一个静态内部链接变量。
^1697351050659

可以看出,rand()函数内部由一个静态内部链接变量 next(称为==种子==)，将next经过魔术公式得出随机结果。静态变量next的初始值是1，其值在每次调用rand0()函数时都会被修改（通过魔术公式）。该函数是用于返回一个==0～32767==之间的值。这也就对应着一个种子生成==一个新的种子==，==新的种子==又去进行rand()，就有了种子==不断更新==。
^1697355805778

当我们运行了一次程序时，很好，得到了不同的==随机数==。我们再运行一次程序，发现该程序得到的随机数与上一次的==相同==。这体现了“伪随机”的一个方面。每次主程序运行，都开始于相同的种子1。可以引入另一个函数srand1()==重置种子==来解决这个问题。关键是要让next成为只供rand1()和srand1()访问的==内部链接静态变量==（srand1()相当于C库中的srand()函数)。把srand1()加入rand1()所在的文件中。[[Anki_随机数和静态变量#固定种子就有固定的随机数]]
^1697355757093

### srand()
[[Anki_随机数和静态变量#srand()和rand()的内部]] 可以看出srand()的作用就是需要无符号整理类型的参数，然后将参数==赋值给==种子next。这样rand()就更新种子而通过魔方公式得到不同的随机数结果了。注意，next是具有内部链接的文件作用域静态变量。这意味着rand1()和srand1()都可以使用它，但是其他文件中的函数==无法访问它==。[[Anki_随机数和静态变量#利用srand()给rand()重置随机数演示]]
^1697355757098

### 通过time()函数自动重置种子
如果 C 实现允许访问一些可变的量（如，时钟系统），可以用这些值（可能会被截断）初始化==种子值==。例如，ANSI C有一个time()函数返回系统时间。虽然时间单元因系统而异，但是重点是该返回值是一个可进行运算的类型，而且其值随着==时间==变化而变化。time()返回值的类型名是==time_t==，具体类型与==系统==有关。这没关系，我们可以使用==强制类型转换==: [[Anki_随机数和静态变量#强制转换]]
^1697355757104

一般而言，time()接受的参数是一个==<font color="#f79646"> time_t</font> 类型==对象的==地址==，而时间值就储存在传入的地址上。当然，也可以传入==空指针==（0）作为参数，这种情况下，只能通过返回值机制来提供值。
^1697355757109



## 问答区












## 代码区 #card
### rand()函数
```
example 12.7
/* rand0.c --生成随机数*/
/* 使用 ANSI C 可移植算法 */
static unsigned long int next = 1; /* 种子 */
unsigned int rand0(void)
{
/* 生成伪随机数的魔术公式 */
next = next * 1103515245 + 12345;
return (unsigned int)(next/ 65536) % 32768;
}
```
### 固定种子就有固定的随机数
```
continous 12.8
/* r_drive0.c -- 测试 rand0()函数 */
/* 与 rand0.c 一起编译*/
#include <stdio.h>
extern unsigned int rand0(void);
int main(void)
{
int count;
for (count = 0; count < 5; count++)
printf("%d\n", rand0());
return 0;
}
```
^1697355757114

### srand()和rand()的内部
```
coutinous 12.9
/* s_and_r.c -- 包含 rand1() 和 srand1() 的文件 */
/* 使用 ANSI C 可移植算法 */
static unsigned long int next = 1; /* 种子 */

int rand1(void)
{
/*生成伪随机数的魔术公式*/
next = next * 1103515245 + 12345;
return (unsigned int)(next/ 65536) % 32768;
}

void srand1(unsigned int seed)
{
next = seed;
}
```

### 利用srand()给rand()重置随机数演示
```
coutinous 12.10
/* r_drive1.c -- 测试 rand1() 和 srand1() */
/* 与 s_and_r.c 一起编译 */
#include <stdio.h>
#include <stdlib.h>
extern void srand1(unsigned int x);
extern int rand1(void);
int main(void)
{
int count;
unsigned seed;
printf("Please enter your choice for seed.\n");
while (scanf("%u", &seed) == 1)
{
srand1(seed);
/* 重置种子 */
for (count = 0; count < 5; count++)
printf("%d\n", rand1());
printf("Please enter next seed (q to quit):\n");
}
printf("Done\n");
return 0;
}
```

### 强制转换
```
#include <time.h> /* 提供time()的ANSI原型*/
srand1((unsigned int) time(0)); /* 初始化种子 */
```
