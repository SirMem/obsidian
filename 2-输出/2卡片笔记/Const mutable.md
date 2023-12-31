---
due: 2023-11-02
title: 常成员函数_卡片
tags:
  - 卡片
  - Cplus
---
# 🍎重点摘抄
## 定义
常成员函数（const member function）是一种类成员函数，它被声明为`const`关键字的一部分。常成员函数的目的是告诉编译器，该函数不会修改调用它的对象的成员变量。这是一种编程约定，用于确保对象的状态不会在常成员函数内部被更改，从而允许这些函数在常量对象上进行调用。

## Const
```cpp
class MyClass {
public:
    // 常成员函数，不修改对象的状态
    void someFunction() const {
        // 只能读取成员变量，不能修改它们
    }
};
```
在常成员函数内部，你只能读取对象的成员变量，不能修改它们。如果试图在常成员函数内部修改成员变量，编译器会报错。这有助于确保常量对象的不可变性，并允许你在常量对象上调用这些函数，而不必担心对象状态的变化。

## Mutable
mutable意为可变的，一般在类中的private声明。可以在const定义的常函数中的内变量进行数值修改。如
```cpp
class Myclass{
public:
	void someFunction()const{
		cout<<"hello,world"<<endl;
		count++; //const常函数不允许对变量进行赋值
	}
private:
	mutable count; //但是使用了mutable就可以进行赋值
}
```
### lambda的处理

## 使用场景
1. 在常量对象上调用成员函数，以确保对象状态不会更改。
2. 允许编译器进行一些性能优化，因为它知道常成员函数不会修改对象的状态，所以可以进行一些优化。
3. 在常量对象上调用常成员函数可以提高代码的可读性，因为它清楚地表明这个函数不会改变对象。
# 📒相关文章




# 🍏引用链接

