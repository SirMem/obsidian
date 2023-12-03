---
due: 2023-11-16 

title: 数组、vertor.array_卡片
tags:
 
- Cplus 卡片
---
# 🍎重点摘抄
## vector
vector的中文翻译为向量，是一种C++ STL中的序列容器。本质上是一个动态数组。它的是存储方式和C++语言本身提供的数组一样都是顺序存储，因此vector的操作和数组十分相似。但是和数组不一样的是，数组的存储空间是静态的，一旦配置了就不能改变，而vector的存储空间是动态的，随着元素的加入，它的内部机制会自动扩充空间以容纳新元素，因此也被称为可变长数组。

## vector的存储机制
vector的动态空间实现如下图所示，
![](https://img-blog.csdnimg.cn/20200219230804596.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80MjI5MjIyOQ==,size_16,color_FFFFFF,t_70)
为了减少空间配置的时间代价，通常vector配置的空间会比我们标注的需求量更大一些，于是vector总的存储空间就如上图所示分成了两部分，其中工作空间是按我们标注的需求配置的，而备用空间就是额外配置的那一部分空间。

当需要扩充的新的空间时，vector会优先使用备用空间。例如我们现在要在末尾插入6，它会将finish <font color="#f79646">迭代器</font>指向的空间用于存储6，最后再调整finish 迭代器的位置。
![](https://img-blog.csdnimg.cn/20200219232845337.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80MjI5MjIyOQ==,size_16,color_FFFFFF,t_70)
当备用空间不足以存放要插入的元素时，vector会在另外较大的空闲空间中配置一块大小为原来两倍的新空间（由于不能保证原空间之后有足有的空闲空间，所以并不是直接在原空间后面接续），然后将原空间中的数据按顺序迁移到新空间，最后释放原来的存储空间。这一过程可以简单记忆为重新配置、移动数据、释放原空间。

下面是以“在备用空间用完的情况下插入新元素3”为例，用图片形式描述前后的存储空间变化。
![](https://img-blog.csdnimg.cn/20200219235717879.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80MjI5MjIyOQ==,size_16,color_FFFFFF,t_70)
由于以上过程对使用者而言都是透明的，所以需要非常注意的一点是，一旦vector的空间重新配置，所有指向原vector的迭代器都会失效！
### 特点和作用
1. **动态大小：** `std::vector` 可以根据需要动态调整大小，可以动态添加或删除元素。
2. **连续内存：** 它以连续的内存块存储元素，可以通过索引快速访问元素。
3. **封装了常见操作：** `std::vector` 提供了许多成员函数来执行常见的操作，如插入、删除、查找元素等。

## vertor的命令
### push_back
在vertor的尾部添加元素。使用方法为object.push_back(value);
### size
计算出元素的总数。
### clear
清空 vector 中的所有元素
### erase
删除指定位置
### begin
### empty
检查 vector 是否为空，如果为空返回 true
## vertor的使用
### 包含头文件
在使用`vertor`之前，需要包含`<vertor>`头文件

### 声明和初始化
vertor的声明和类,结构体类似，都需要声明一个对象。
```cpp
std::vertor<typename> object;
//有了对象之后，才可以在对象内进行动态存储操作
//如
std::vertor<int> vec; // 声明一个空的类型vertor
//也可以进行初始化
std::vertor<int> vec2(5,0);//声明一个包含5个整数元素的 vector，5个整数元素的初始值都为0
vector<string> vec3 = {"apple", "banana", "orange"};// 声明并初始化一个 vector
```

### 添加元素
```cpp
//如
vec.push_back(10); // 在 vector 尾部添加元素 10
```

### 访问元素
```cpp
cout << vec[0]; // 输出第一个元素的值
// 遍历输出所有元素
for (int i = 0; i < vec.size(); ++i) {
    cout << vec[i] << " ";
}
// 使用迭代器遍历输出所有元素
for (auto it = vec.begin(); it != vec.end(); ++it) {
    cout << *it << " ";
}
// 使用范围-based for 循环遍历输出所有元素（C++11及以后版本）
for (const auto& elem : vec) {
    cout << elem << " ";
}
```
### 删除操作
```cpp
vec.pop_back(); // 删除 vector 尾部的元素
// 删除指定位置（例如，删除第一个元素）
vec.erase(vec.begin()); // 或者使用 vec.erase(vec.begin() + index);
```
# 📒相关文章




# 🍏引用链接
[[迭代器]]
[[堆栈]]  push_back