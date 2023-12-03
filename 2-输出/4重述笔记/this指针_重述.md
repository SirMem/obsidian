---
due: 2023-12-03 

title: this指针_重述
tags:
 
- Cplus 重述
---


> [!summary]+ summary
> 说明了this指针的机制


# 🤔问题:





# 🤔相关联:




# 📘自我重述
## 基本定义
在C++中，`this`是一个特殊的指针，它在每个类的非静态成员函数中都存在。`this`指针指向调用当前成员函数的那个对象。换句话说，`this`指针是一个自引用指针。当调用一个类的成员函数时，编译器会隐式地传递一个指向当前对象的`this`指针作为函数的隐藏参数。
![[Pasted image 20231203170501.png|500]]

## 用途
### 区分成员变量和函数参数
当函数参数与成员变量同名时，可以使用`this`指针来区分它们。
```cpp
```
### 链式调用
```cpp
Stack& push(int value) {
    Node* newNode = new Node;
    newNode->data = value;
    newNode->next = top;
    top = newNode;
    return *this;
}
```
### 在构造函数中检查对象是否被正确构造
### 实现流畅的接口


# 💻代码区