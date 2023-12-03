---
due: 2023-11-24 

title: Cmake的使用_卡片
tags:
 
- cmake 卡片
---
# 🍎重点摘抄
## 注释
### 行注释
`CMake`使用 `#`进行行注释,可以放在任何位置
```cmake
# 这是一个 CMakeLists.txt 文件
cmake_minimum_required(VERSION 3.0.0)
```
### 注释块
CMake 使用 `#[[ ]]`形式进行块注释。
```cmake
#[[ 这是一个 CMakeLists.txt 文件。
这是一个 CMakeLists.txt 文件
这是一个 CMakeLists.txt 文件]]
```

## 基本执行
接下来依次介绍一下在 CMakeLists.txt 文件中添加的三个命令:
### cmake_minimum
cmake_minimum_required：指定使用的 cmake 的最低版本
可选，非必须，如果不加可能会有警告

### project
project：定义工程名称，并可指定工程的版本、工程描述、web主页地址、支持的语言（默认情况支持所有语言），如果不需要这些都是可以忽略的，只需要指定出工程名字即可。
```cmake
# PROJECT 指令的语法是：
project(<PROJECT-NAME> [<language-name>...])
project(<PROJECT-NAME>
       [VERSION <major>[.<minor>[.<patch>[.<tweak>]]]]
       [DESCRIPTION <project-description-string>]
       [HOMEPAGE_URL <url-string>]
       [LANGUAGES <language-name>...])
add_executable：定义工程会生成一个可执行程序
```

### add_executable
add_executable(可执行程序名 源文件名称)
这里的可执行程序名和project中的项目名没有任何关系
源文件名可以是一个也可以是多个，如有多个可用空格或;间隔

```cmake
# 样式1
add_executable(app add.c div.c main.c mult.c sub.c)
# 样式2
add_executable(app add.c;div.c;main.c;mult.c;sub.c)
```

## 执行cmake
将 `CMakeLists.txt` 文件编辑好之后，就可以执行 cmake命令
根据终端所在路径在终端中输入cmake CmakeList当前路径
生成makefile文件，再输入make




# 🍏引用链接

