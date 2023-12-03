---
due: 2023-10-19 

title: Connect_指针数组在函数的应用
tags:
 
- c语言 Connection
---

# 🤔问题:
## 指针数组在函数中有什么应用
将数组传递给函数
修改数组的元素
动态分配数组





# 🤔相关联:
[[Connect_指针和数组]]
[[指针]]
[[数组]]





# 📘自我重述:
## 数组作函数的形参
你可以将数组作为参数传递给函数，函数可以使用数组指针来访问和处理数组的元素。![[Connect_指针数组在函数的应用#数组作函数形参]]
## 函数修改数组的元素
通过传递数组指针给函数，函数可以修改数组的元素，这种修改在函数外部也是可见的。![[Connect_指针数组在函数的应用#函数修改数组元素]]

## 指针函数
C语言的指针函数是一个函数，其返回类型是指针类型。指针函数允许你返回一个指向某种数据类型的指针，而不是返回实际的数据。这种函数非常有用，因为它们可以用来动态分配内存、返回数组或结构体等数据结构，以及在函数之间传递复杂的数据。
## 动态分配数组
可以在函数内部使用指针和内存分配函数（如`malloc`）来动态分配数组的内存。![[Connect_指针数组在函数的应用#动态分配数组代码]]






# 代码区
### 数组作函数形参
```
void printArray(int arr[], int size) {
    for (int i = 0; i < size; i++) {
        printf("%d ", arr[i]);
    }
}
//形参arr[] 在这个代码中并没有特定的意义，它只是一个占位符，用来接收传递给函数的数组。你可以将arr修改成你喜欢的名字。
int main() {
    int myArray[] = {1, 2, 3, 4, 5};
    int size = sizeof(myArray) / sizeof(myArray[0]);
    printArray(myArray, size);
    return 0;
}
```

### 函数修改数组元素
```
void modifyArray(int arr[], int size) {
    for (int i = 0; i < size; i++) {
        arr[i] *= 2;
    }
}

int main() {
    int myArray[] = {1, 2, 3, 4, 5};
    int size = sizeof(myArray) / sizeof(myArray[0]);
    modifyArray(myArray, size);
    // myArray 现在包含 {2, 4, 6, 8, 10}
    return 0;
}

```


### 动态分配数组代码
```
int *createDynamicArray(int size) {
    int *arr = (int *)malloc(size * sizeof(int));
    return arr;
}

void freeDynamicArray(int *arr) {
    free(arr);
}

int main() {
    int size = 5;
    int *dynamicArray = createDynamicArray(size);
    // 使用 dynamicArray
    freeDynamicArray(dynamicArray); // 释放内存
    return 0;
}


```