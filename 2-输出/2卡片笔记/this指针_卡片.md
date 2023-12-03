---
due: 2023-11-03
title: this指针_卡片
tags:
  - 卡片
  - Cplus
---
# 🍎重点摘抄
this指针是一个定义在非静态成员函数当中的一个指针。该指针指向当前调用的对象
通过 `this` 指针，你可以访问当前对象的成员变量和成员函数，以及在函数内部引用当前对象的其他属性。
```cpp
#include <iostream>

class MyClass {
public:
    MyClass(int value) : value(value) {}
    
    void printValue() {
        std::cout << "Value: " << this->value << std::endl;
    }

private:
    int value;
};

int main() {
    MyClass obj(42);
    obj.printValue();
    return 0;
}

```


# 📒相关文章




# 🍏引用链接

