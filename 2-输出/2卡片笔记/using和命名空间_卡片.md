---
due: 2023-11-29 

title: using和命名空间_卡片
tags:
 
- Cplus 卡片
---
# 🍎重点摘抄
## namespece
在C++中，命名空间（Namespace）是一种用来避免命名冲突并组织代码的机制。它允许开发者将代码分组到一个特定的命名空间中，从而创建了一个作用域，其中的标识符（变量、函数、类等）在该命名空间内部是唯一的。

命名空间有助于避免在大型项目中出现名称冲突，特别是当多个库、模块或者不同来源的代码需要被整合时。通过将相关的代码放置在特定的命名空间中，可以确保在同一个命名空间内的标识符不会与其他命名空间中的标识符发生冲突。

使用命名空间的语法示例如下：

```cpp
// 定义命名空间
namespace MyNamespace {
    // 声明一些变量、函数、类等
    int myVariable;
    void myFunction();
    class MyClass {
        // 类定义
    };
}

// 使用命名空间中的内容
int main() {
    // 访问命名空间中的变量
    MyNamespace::myVariable = 42;

    // 调用命名空间中的函数
    MyNamespace::myFunction();

    // 创建命名空间中的类的实例
    MyNamespace::MyClass obj;

    return 0;
}
```

这样，使用命名空间可以使代码更加模块化和可维护，避免了命名冲突，并提高了代码的可读性和可重用性。

## namespace的使用规范
在 C++ 中，命名空间的作用域规则意味着在 `main()` 函数之外，因此需要再main()外部创建namespace
## using
在C++中，`using` 关键字用于简化代码、引入命名空间中的标识符或者特定类型到当前作用域，以便更方便地使用它们。

有两种常见的使用情况：

1. **使用命名空间中的标识符**：`using namespace` 语句允许将整个命名空间中的所有标识符引入到当前作用域中。这样做可以避免重复输入命名空间的名称，但有时可能会导致命名冲突。

    示例：
    ```cpp
    // 引入命名空间中的所有标识符
    using namespace std;

    int main() {
        // 不需要再写 std::
        cout << "Hello, world!" << endl;

        return 0;
    }
    ```

2. **使用特定类型或标识符**：`using` 关键字也可以用于引入特定命名空间中的特定标识符或类型到当前作用域。

    示例：
    ```cpp
    // 引入命名空间中的特定标识符或类型
    using std::cout;
    using std::endl;

    int main() {
        // 可以直接使用引入的标识符，无需使用 std::
        cout << "Hello, world!" << endl;

        return 0;
    }
    ```

需要注意的是，`using` 语句可能会引起命名冲突，因此过度使用 `using namespace` 可能会导致不可预料的问题。最佳实践是尽可能只引入需要的标识符或类型，以减少命名冲突的可能性。



# 📒相关文章




# 🍏引用链接

