---
due: 2023-10-26
title: typedef_重述
tags:
  - c语言
  - 重述
---


> [!summary]+ summary
> 简要说明typedef的用法


# 🤔问题:
## typedef有什么作用
提高代码的可读性和可维护性。
创建对象的接口


# 🤔相关联:
[[限定符_重述]]
[[指针_重述]]
[[结构体、共用体_重述]]

# 📘自我重述
## 概念
`typedef` 是C语言中的一个关键字，用于创建自定义<font color="#f79646">类型</font>别名。它的主要作用是为现有的数据类型（如基本数据类型或用户定义的结构体、联合体等）创建一个新的名称，以提高代码的可读性和可维护性。

## 基本语法
```
typedef existing_type new_type_name;
```
- `existing_type` 是现有的数据类型，可以是基本数据类型（如 `int`、`char`）、指针、结构体、联合体等。
- `new_type_name` 是你希望创建的自定义类型别名。
- 创建函数指针的别名的方式比较特别 [[指针函数和回调函数_卡片]]

## 常见应用
**创建自定义类型别名**：最常见的用法是为现有数据类型创建易于理解的别名，从而提高代码的可读性。例如，你可以为整数类型创建别名：
```
typedef int Age;
Age myAge = 25; //将int数据类型等价于自命名Age类型
```

**增强可移植性**：`typedef` 可用于提高代码的可移植性，通过创建与数据类型相关的自定义别名，可以轻松适应不同平台的数据类型差异。
```
typedef unsigned long long int MyUInt64; // 可移植的64位无符号整数别名
MyUInt64 value = 1000000000ULL; // 使用别名
```

**简化复杂类型**：对于复杂的数据类型，如指向函数指针的指针，`typedef` 可以简化其使用。
```
typedef void (*FunctionPointer)(int); // 函数指针别名
FunctionPointer myFuncPtr = someFunction; //等价于void(*myFuncPtr)(int) =someFunction
```

**提高可读性**：使用 `typedef` 可以使代码更易阅读和理解，特别是当你需要在多处使用相同的数据类型时。
```
typedef struct {
    int x;
    int y;
} Point; //声明了一个Point类型，为struct

Point origin = {0, 0}; //结构体变量origin初始化内部结构体变量
//origin是对象
```

**封装复杂数据结构**：`typedef` 可以用于封装复杂的数据结构，从而使数据结构的使用更加简单。
```
typedef struct {
    int day;
    int month;
    int year;
} Date;

Date birthday = {15, 10, 1990};
```
# 💻代码区