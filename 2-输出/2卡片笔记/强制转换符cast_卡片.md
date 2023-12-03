---
due: 2023-12-02 

title: 强制转换符cast_卡片
tags:
 
- Cplus 卡片
---
# 🍎重点摘抄

**dynamic_cast 运算符：** `dynamic_cast` 运算符用于在继承层次结构中进行安全的向下类型转换（downcasting）。它能够检查对象的实际类型，并在转换有效时返回指向派生类的指针。 [[RTTI_卡片]]

**const_cast：** `const_cast` 运算符用于在指针或引用中添加或移除 `const` 修饰符或 `volatile` 修饰符。它可以取消对象的 `const` 属性，但要注意，修改 `const` 对象可能会导致未定义行为。
```cpp
const int num = 10;
int* ptr = const_cast<int*>(&num); // 取消 num 的 const 属性

*ptr = 20; // 修改 num，潜在的未定义行为
```

**reinterpret_cast：** `reinterpret_cast` 运算符用于执行不同类型之间的强制类型转换。它能够将一个指针类型转换为另一个不同类型的指针，或者将任何整数类型转换为指针类型，但是使用时需要非常小心，因为它可能会导致不安全或未定义的行为。
```cpp
int value = 10;
void* voidPtr = reinterpret_cast<void*>(&value); // 转换为 void* 指针类型
```
# 📒相关文章




# 🍏引用链接

