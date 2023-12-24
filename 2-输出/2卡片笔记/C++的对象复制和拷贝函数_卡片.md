---
due: 2023-11-21
title: C++的对象复制和拷贝函数_卡片
tags:
  - Cplus
  - 卡片
---
# 🍎重点摘抄
在C++中，当涉及到对象的复制时，有两种不同类型的拷贝：浅拷贝和深拷贝。

1. **浅拷贝**：
   - 浅拷贝是指将一个对象的值复制到另一个对象，但是只是简单地复制对象的成员变量的值，而不复制指向动态分配内存的指针。因此，原始对象和拷贝对象将共享相同的内存地址，当其中一个对象修改了共享内存中的内容，另一个对象的内容也会相应改变。
   - 对于含有动态分配内存或指针的类，浅拷贝并不能完全复制对象。这可能导致意外的行为，特别是当你试图释放相同的内存空间两次时，会产生悬挂指针的问题。

   
2. **深拷贝**：
   - 深拷贝是在进行对象复制时，会分配新的内存空间，并将源对象的内容复制到新分配的内存中。这样，源对象和拷贝对象拥有各自独立的内存空间，修改其中一个对象的内容不会影响另一个对象。
   - 对于含有动态分配内存或指针的类，深拷贝是非常重要的，因为它确保每个对象都有自己独立的内存空间。


总之，深拷贝和浅拷贝的区别在于它们是否复制了动态分配内存的内容。深拷贝会为目标对象分配新的内存空间，并复制原始对象的内容到新的内存中，而浅拷贝仅是简单地复制对象的成员变量值，导致原始对象和拷贝对象共享相同的内存地址。
```cpp
#include <iostream>
class house{

    private:

        void* pkey;

        int Area;

    public:

        house(int area) : Area(area),pkey(nullptr)

        {

            pkey = new int[Area]; //创建一个大小为int*area的内存空间

        }

        ~house()

        {

            free(pkey);

            pkey = nullptr;

        }

    void where() const

    {

        std::cout << "Hello,I live in" << pkey << std::endl;

    }

  

    house(const house& h):Area(h.Area),pkey(nullptr) //深拷贝函数
    {
        pkey = new int[Area];
    } //重载构造函数
};
int main(){
    house h1(100);
    h1.where();
    house h2 = h1;
    h2.where();
    return 0;
}
```

> [!attention] 
>  总的来说，浅拷贝和深拷贝的区别在于对象复制时是否创建了共享的动态分配资源的独立副本

# 📒相关文章




# 🍏引用链接

https://www.bilibili.com/video/BV1BS4y1K7Au/?spm_id_from=333.337.search-card.all.click&vd_source=8b450300cfa6415cb0312754cf65ba30