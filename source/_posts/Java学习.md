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

<iframe>
    <!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>PyG2Plot</title>
    <script type="text/javascript" src="https://unpkg.com/@antv/g2plot@2"></script>
</head>
<body>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    html, body, div.pyg2plot-plot-container { 
      height: 100%;
      overflow: hidden;
    }
  </style>

  <div id="b70299169ec042f5a0ba3ca4bd78068f" class="pyg2plot-plot-container"></div>

  <script>
    var plot_b70299169ec042f5a0ba3ca4bd78068f = new G2Plot.Bar("b70299169ec042f5a0ba3ca4bd78068f", {
  "appendPadding": 66,
  "data": [
    {
      "year": "1951 \u5e74",
      "value": 38
    },
    {
      "year": "1952 \u5e74",
      "value": 52
    },
    {
      "year": "1956 \u5e74",
      "value": 999
    },
    {
      "year": "1957 \u5e74",
      "value": 145
    },
    {
      "year": "1958 \u5e74",
      "value": 48
    },
    {
      "year": "1959 \u5e74",
      "value": 666
    },
    {
      "year": "1951 \u5e74",
      "value": 38
    },
    {
      "year": "1951 \u5e74",
      "value": 38
    },
    {
      "year": "1951 \u5e74",
      "value": 38
    },
    {
      "year": "1951 \u5e74",
      "value": 38
    },
    {
      "year": "1951 \u5e74",
      "value": 38
    },
    {
      "year": "1951 \u5e74",
      "value": 38
    },
    {
      "year": "1951 \u5e74",
      "value": 38
    },
    {
      "year": "1951 \u5e74",
      "value": 38
    }
  ],
  "xField": "value",
  "yField": "year",
  "seriesField": "year",
  "legend": false
}); 
    plot_b70299169ec042f5a0ba3ca4bd78068f.render();
  </script>
</body>
</html>
</iframe>