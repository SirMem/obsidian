---
due: 2023-12-02 

title: RTTI_卡片
tags:
 
- Cplus 卡片
---
# 🍎重点摘抄
C++中的RTTI（Run-Time Type Identification，运行时类型识别）是一种机制，允许程序在运行时确定对象的实际类型。RTTI允许程序查询对象的类型信息，并进行相应的操作，如确定对象的实际类型、处理多态对象、进行类型转换等。

在C++中，RTTI主要通过两种方式实现：

1. **`typeid` 运算符：** `typeid` 运算符允许获取对象的类型信息。它返回一个 `std::type_info` 对象，表示表达式的静态类型。

   示例：

   ```cpp
   #include <iostream>
   #include <typeinfo>

   class Base {
       virtual void dummy() {} // 声明虚函数
   };

   class Derived : public Base {};

   int main() {
       Base* basePtr = new Derived(); //向上转型

       if (typeid(*basePtr) == typeid(Derived)) { 
           std::cout << "basePtr 指向 Derived 类型的对象" << std::endl;
       }

       delete basePtr;
       return 0;
   }
   ```

2. **`dynamic_cast` 运算符：** `dynamic_cast` 运算符用于在继承层次结构中进行安全的向下类型转换（downcasting）。如果转换有效，它会返回指向派生类的指针；如果转换失败，则返回空指针（对于指针类型）或抛出 `std::bad_cast` 异常（对于引用类型）。

   示例：

   ```cpp
   #include <iostream>

   class Base {
       virtual void dummy() {} // 声明虚函数
   };

   class Derived : public Base {};

   int main() {
       Base* basePtr = new Derived();
       Derived* derivedPtr = dynamic_cast<Derived*>(basePtr);

       if (derivedPtr) {
           std::cout << "转换成功" << std::endl;
       } else {
           std::cout << "转换失败" << std::endl;
       }

       delete basePtr;
       return 0;
   }
   ```

RTTI使得在运行时可以进行类型识别和转换，但它有一定的开销和限制。需要注意的是，对于没有虚函数的类或基类对象，`typeid` 和 `dynamic_cast` 可能无法正确识别类型，因为RTTI依赖于虚函数表（vtable）来实现。




# 📒相关文章




# 🍏引用链接

