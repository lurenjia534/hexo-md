---
title: Java学习
categories: Java
tags: 
     - Java
     - 代码
     - 解释&编译型语言
---

## 工具和环境

- 使用工具 [Vscode](https://code.visualstudio.com/)

- 环境 JDK-SE-11

## 开始

```Java
package J1;

public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello World");
    }
}
```
<!--more-->
### 解释

```Java
package J1; // 项目名

public class HelloWorld // 包名

public static void main(String[] args) // 主类

System.out.println("Hello World"); // 打印输出Hello Word
```

## 变量定义与运算

```Java
package J1;

public class J2 {
    public static void main(String[] args) {
        int a=3,b=5,sum;
        sum=a+b;
        System.out.println(sum);
    }
}
```

### 解释-变量定义与运算

```Java
    int a=3,b=5,sum; // 定义整形int变量AB和Sum变量

    sum=a+b; // sum等于A+B
```

## 循环

### do while

```java
    package J1;

public class xunhuan {
    public static void main(String[] args) {
        int x = 10;
        do{
            x++;
            System.err.println(x);
        }while(x < 20);
    }
}

```

### 解释-do while

do while至少循环一次

```java
 while( 布尔表达式 ) {
  //循环内容
}
````

```java
    do {
       //代码语句
}while(布尔表达式);

```
