---
due: 2023-11-06 

title: C++的文件与流_卡片
tags:
 
- Cplus 卡片
---
# 🍎重点摘抄
## 库
|数据类型|描述|
|---|---|
|ofstream|该数据类型表示输出文件流，用于创建文件并向文件写入信息。|
|ifstream|该数据类型表示输入文件流，用于从文件读取信息。|
|fstream|该数据类型通常表示文件流，且同时具有 ofstream 和 ifstream 两种功能，这意味着它可以创建文件，向文件写入信息，从文件读取信息。|

要在 C++ 中进行文件处理，必须在 C++ 源代码文件中包含头文件 iostream 和 fstream。

## 打开文件
在从文件读取信息或者向文件写入信息之前，必须先打开文件。**ofstream** 和 **fstream** 对象都可以用来打开文件进行写操作，如果只需要打开文件进行读操作，则使用 **ifstream** 对象。

下面是 open() 函数的标准语法，open() 函数是 fstream、ifstream 和 ofstream 对象的一个成员。
```cpp
void open(const char *filename, ios::openmode mode);
```
**open()** 成员函数的第一参数指定要打开的文件的名称和位置，第二个参数定义文件被打开的模式

| 模式标志   | 描述                                                                   |
| ---------- | ---------------------------------------------------------------------- |
| ios::app   | 追加模式。所有写入都追加到文件末尾。                                   |
| ios::ate   | 文件打开后定位到文件末尾。                                             |
| ios::in    | 打开文件用于读取。                                                     |
| ios::out   | 打开文件用于写入。                                                     |
| ios::trunc | 如果该文件已经存在，其内容将在打开文件之前被截断，即把文件长度设为 0。 ||                                                                        |

可以把以上两种或两种以上的模式结合使用。例如，如果您想要以写入模式打开文件，并希望截断文件，以防文件已存在，那么您可以使用下面的语法：
```cpp
ofstream outfile; //创建对象
outfile.open("file.dat", ios::out | ios::trunc );
```
## 关闭文件

当 C++ 程序终止时，它会自动关闭刷新所有流，释放所有分配的内存，并关闭所有打开的文件。但程序员应该养成一个好习惯，在程序终止前关闭所有打开的文件。
下面是 close() 函数的标准语法，close() 函数是 fstream、ifstream 和 ofstream 对象的一个成员。
```cpp
void close();
outfile.close(); //对象
```

## 写入文件

在 C++ 编程中，我们使用流插入运算符（ << ）向文件写入信息，就像使用该运算符输出信息到屏幕上一样。唯一不同的是，在这里您使用的是 **ofstream** 或 **fstream** 对象，而不是 **cout** 对象。
```cpp
ofstream outfile;
outfile << "Hello" << endl; //向写入对象写入数据
```
## 读取文件

在 C++ 编程中，我们使用流提取运算符（ >> ）从文件读取信息，就像使用该运算符从键盘输入信息一样。唯一不同的是，在这里您使用的是 **ifstream** 或 **fstream** 对象，而不是 **cin** 对象。
```cpp
ifstream infile;
infile >> data; //读入一个数组，或字符串
```


# 📒相关文章
https://www.runoob.com/cplusplus/cpp-files-streams.html
# 🍏引用链接

https://www.runoob.com/cplusplus/cpp-files-streams.html