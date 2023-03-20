---
title: Java基础 - 变量、常量
---

当你编写Java程序时，你需要用到变量、常量和数据类型。这些概念是Java语言中的基础概念，理解它们对于成为一名优秀的Java程序员至关重要。下面详细介绍Java中的变量、常量和数据类型。

## 变量

变量是Java程序中用于存储数据的一种基本工具。在Java中，变量有以下几个特点：

- 变量必须先声明再使用。
- 变量在声明时需要指定其数据类型。
- 变量可以被赋予新值，而其数据类型不能改变。
- 变量的命名要符合标识符的命名规则。

以下是一个Java中变量的声明和使用的例子：

```java
//声明一个整型变量
int num;
//给变量赋值
num = 10;
//输出变量的值
System.out.println(num); //输出10
```

## 常量
常量是在程序运行期间值不能改变的量，它们的值一旦被确定就不能被改变。在Java中，常量使用关键字`final`来定义。常量的命名要符合标识符的命名规则，通常使用全大写字母来命名。以下是Java中常量的定义和使用的例子：

```java
//定义一个整型常量
final int MAX_NUM = 100;
//尝试修改常量的值会导致编译错误
MAX_NUM = 200; //编译错误：无法为最终变量MAX_NUM分配值
//输出常量的值
System.out.println(MAX_NUM); //输出100
```