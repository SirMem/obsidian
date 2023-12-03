---
due: 2023-10-24 

title: 结构体Struct_重述
tags:
 
- c语言 重述
---


> [!summary]+ summary
> 


# 🤔问题:





# 🤔相关联:
[[位域_卡片]]
[[共用体_卡片]]


# 📘自我重述
## 概念
结构体是C语言中一种用户定义的数据类型，它允许将不同类型的数据组合在一起，以创建自定义的数据结构。结构体的每个成员可以具有不同的数据类型，这使得它非常适合表示和组织复杂的数据。
## 定义结构
结构体定义由关键字 struct 和结构体名组成，结构体名可以根据需要自行定义。struct 语句定义了一个包含多个成员的新的数据类型，struct 基本构架语句的格式如下：
```
struct structure_name {
    data_type member1;
    data_type member2;
    // ...
};
```
例如定义一个结构体:
```
struct Person {
    char name[50];
    int age;
    float height;
};
```
## 结构体变量
在定义了结构体后，要使用结构体则必须声明结构变量，声明方法如下:
```
struct Person person1;
struct Person person2;
```
结构体变量是独立的，也就是说结构体类似一个函数，而结构体变量类似于形参，将内容传给结构体。如
```
struct Point {
    int x;
    int y;
};

int main() {
    struct Point p1; // 第一个结构体变量
    p1.x = 10;
    p1.y = 20;

    struct Point p2; // 第二个结构体变量
    p2.x = 30;
    p2.y = 40;

    // 两个结构体变量分别存储不同的数据
    printf("Point 1: (%d, %d)\n", p1.x, p1.y);
    printf("Point 2: (%d, %d)\n", p2.x, p2.y);

    return 0;
}

```
## 访问结构体成员
有了结构体变量之后，就可以利用结构体变量对结构体内部变量进行访问，如
```
person1.age = 30;
person1.height = 175; //结构体变量给结构体内部赋值
strcpy(person1.name,"KennyS") //通过strcpy函数给person1.name赋字符串类型的值
```
## 结构体初始化
在有了结构体的基本声明后。结构体可以在声明时初始化，也可以后续初始化。例如：
```
//声明时初始化
struct Person {
    char name[50] = "KennyS";
    int age = 29;
    float height = 170.2;
};

//在有了结构后的后续初始化
//已有结构
struct Person {
    char name[50];
    int age;
    float height;
};
//进行后续初始化
struct Person person3 = {"Alice", 25, 160.0};
```
## 结构体作为函数参数及形参
结构体可以作为函数参数传递，以便在函数中操作结构体数据。
```
void printPerson(struct Person p) {
    printf("Name: %s, Age: %d, Height: %.2f\n", p.name, p.age, p.height);
}
//`void printPerson(struct Person p)` 只是一个示例，你可以根据需要为参数和变量选择更具描述性的名称，以使代码更易于理解和维护。
```

## 结构体指针
可以使用指向结构体的指针来操作结构体数据。例如：
```
struct Person *ptr = &person1;
ptr->age = 31;
//让我们逐步解释它的含义
1. `struct Person *ptr`：这是一个声明语句，它声明了一个指向结构体 `Person` 的指针变量，命名为 `ptr`。这个指针可以用来存储结构体 `Person` 类型的变量的地址。
2. `&person1`：`&` 操作符用于获取变量 `person1` 的地址。在这里，`person1` 应该是一个结构体类型的变量。
3. `ptr = &person1`：这一行将指针变量 `ptr` 设置为指向 `person1` 结构体变量的地址。现在，`ptr` 包含了 `person1` 的地址。
4. `ptr->age = 31`：这一行使用指针 `ptr` 来访问 `person1` 结构体变量的成员 `age`，并将其设置为 `31`。`->` 操作符用于通过指针访问结构体成员，因为 `ptr` 包含了结构体的地址，所以它可以用来访问结构体成员，就像它是一个结构体一样。
5. 总结：这段代码的目的是将一个指向 `person1` 结构体变量的指针命名为 `ptr`，然后使用该指针来修改 `person1` 结构体的 `age` 成员的值，将其设置为 `31`。
```

## 嵌套结构体
结构体可以嵌套在其他结构体中，以创建更复杂的数据结构。这样可以表示更复杂的关系和层次结构。
```
struct Address {
    char street[100];
    char city[50];
    char zip[10];
};

struct Contact {
    struct Person person;
    struct Address address;
};
```
### 访问嵌套结构体
#### 常规访问
要访问嵌套结构体内部的值，你需要使用多个`.`或`->`操作符，根据结构体的类型和访问路径来访问内部成员。
假设有以下嵌套的结构体:
```
struct Address {
    char street[100];
    char city[50];
    char zip[10];
};

struct Contact {
    char email[100];
    struct Address address;
};
```
现在，我们将访问`Contact`结构体内部的`Address`结构体的`city`成员的值：
```
struct Contact myContact; //建立一个Contact的变量

// 访问 Contact 结构体中的 Address 结构体
strcpy(myContact.email, "example@email.com");

// 访问 Address 结构体内部的 city 成员
strcpy(myContact.address.city, "New York");
```
我们首先访问了`myContact`结构体中的`email`成员。然后，使用`.`操作符，我们进一步访问了`address`结构体，并在其中使用`.`操作符访问了`city`成员
#### 指针访问
如果你有一个指向嵌套结构体的指针，你可以使用`->`操作符来访问成员,例如：
```
struct Contact *ptr = &myContact; //创建了一个Contact结构类型的指针，并被赋值myContact变量地址
strcpy(ptr->address.city, "Los Angeles"); //通过myContact访问address.city，并完成赋值字符串
```

## sizeof操作符
使用`sizeof`操作符可以获取结构体的大小，这对于内存分配和处理非常有用。
```
size_t size = sizeof(struct Person);
```

## 位域(bit Fields)
C语言允许在结构体中定义位域，用于节省内存，尤其在嵌入式系统中很有用。
```
struct Flags {
    unsigned int flag1 : 1;
    unsigned int flag2 : 1;
    // 更多位域...
};
```




# 💻代码区