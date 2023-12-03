---
due: 2023-10-24 

title: strcpy_卡片
tags:
 
- c语言 卡片
---
# 🍎重点摘抄

`strcpy` 是C语言标准库中的一个字符串操作函数，用于将一个字符串复制到另一个字符串中。它的原型定义在 `<string.h>` 头文件中，并有以下格式：
```
char *strcpy(char *destination, const char *source);
```
- `destination` 是目标字符串，它是一个字符数组（C字符串），用来存储源字符串的副本。
- `source` 是源字符串，它是一个以 null 结尾的字符数组（C字符串），它的内容将被复制到目标字符串中。

`strcpy` 函数将源字符串的内容复制到目标字符串中，直到遇到源字符串的 null 终止符（`\0`）为止。它会复制整个字符串，包括 null 终止符。


## 案例
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
# 📒相关文章




# 🍏引用链接

