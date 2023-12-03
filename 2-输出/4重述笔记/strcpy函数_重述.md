---
due: 2023-10-25
title: strcpy函数_重述
tags:
  - c语言 重述
cards-deck: 2-输出::4重述笔记
---


> [!summary]+ summary
> 简要说明strcpy函数的使用

#card
# 🤔问题:
## 如何防止strcpy调用导致的缓冲区溢出
使用动态分配内存或者换一个函数
# 🤔相关联:
[[分配内存_重述]]



# 📘自我重述
## 定义
`strcpy` 是C语言标准库中的一个字符串操作函数，用于将一个字符串复制到另一个字符串中。它的原型定义在 `<string.h>` 头文件中，并有以下格式：
```
char *strcpy(char *destination, const char *source);
```
- `destination` 是目标字符串，它是一个字符数组（C字符串），用来存储源字符串的副本。
- `source` 是源字符串，它是一个以 null 结尾的字符数组（C字符串），它的内容将被复制到目标字符串中。

`strcpy` 函数将源字符串的内容复制到目标字符串中，直到遇到源字符串的 null 终止符（`\0`）为止。它会复制整个字符串，包括 null 终止符。

## 例子
```
#include <stdio.h>
#include <string.h>

int main() {
    char source[] = "Hello, World!";
    char destination[20]; // 目标字符串数组，足够大以容纳源字符串

    strcpy(destination, source); // 复制源字符串到目标字符串

    printf("Source: %s\n", source);
    printf("Destination: %s\n", destination);

    return 0;
}
```

在这个示例中，`strcpy` 函数将源字符串 "Hello, World!" 复制到目标字符串 `destination` 中。请注意，为了确保目标字符串足够大以容纳源字符串，你需要提前分配足够的内存。否则，可能会导致缓冲区溢出和不可预测的行为

## 防止缓存区溢出
### 使用动态内存分配
如果你不确定要复制的字符串的长度，可以使用动态内存分配函数（如`malloc`和`strdup`）来创建足够大的缓冲区，以容纳字符串。这样可以确保不会发生缓冲区溢出。
```
const char* src = "This is a potentially long string";
char* dest = (char*)malloc(strlen(src) + 1);
if (dest) {
    strcpy(dest, src);
    // 使用dest
    free(dest); // 不要忘记释放动态分配的内存
}
```
# 💻代码区
