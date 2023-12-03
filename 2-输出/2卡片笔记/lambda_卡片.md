---
due: 2023-12-02 

title: lambda_卡片
tags:
 
- Cplus 卡片
---
# 🍎重点摘抄
在C++中，lambda表达式是一种能够定义匿名函数的特性。它允许您在需要函数的地方创建一个函数对象，而不必显式地定义一个函数。Lambda表达式通常用于函数式编程和STL（标准模板库）算法中。

Lambda表达式的一般语法如下：
```
[capture clause] (parameters) -> return_type {  
    // 函数体
    // 可以是一系列语句或表达式
}
```

解释一下各个部分：
- **capture clause（捕获列表）**：可以捕获外部变量，以便在lambda函数体内使用。捕获列表使用中括号 `[]` 括起来。捕获列表可以为空，也可以按值捕获变量 `[var]` 或按引用捕获变量 `[&var]`，甚至混合使用 `[var, &var2]`。
- **parameters（参数）**：与普通函数的参数列表类似，可以为空或包含参数。这是可选的，就像定义普通函数时一样。
- **return_type（返回类型）**：指定lambda表达式的返回类型。这是可选的，编译器可以推断返回类型，但如果lambda表达式有多个返回语句或需要明确指定返回类型时，则需要指定返回类型。
- **函数体**：包含lambda表达式要执行的语句或表达式。

示例：
```cpp
#include <iostream>

int main() {
    // Lambda表达式示例
    int a = 5;
    int b = 10;

    // 使用lambda表达式求和
    auto sum = [a, &b] () -> int {
        b = 20; // 修改b，因为使用了引用捕获
        return a + b;
    };

    std::cout << "Sum: " << sum() << std::endl; // 输出 Sum: 25
    std::cout << "Modified b: " << b << std::endl; // 输出 Modified b: 20

    return 0;
}
```

在这个示例中，lambda表达式通过捕获变量 `a` 和 `b`，使用引用捕获的方式修改了变量 `b` 的值，并返回了 `a + b` 的结果。

## lambda两种运用方式
```cpp
#include <iostream>

  

int main(){

    int a, b;

    b = 10;

    std::cin >> a;

    int  sum = [&a,&b](int c){

        return a + b + c;

    }(5); //传入参数式

    auto sum2 = [&a,&b](int c){

        return a + b + c;

    }; //调用参数式

    std::cout << sum << std::endl;

    std::cout << sum2(5) << std::endl;

}
```


# 📒相关文章




# 🍏引用链接

