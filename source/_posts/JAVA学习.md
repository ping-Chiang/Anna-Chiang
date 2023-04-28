---
title: JAVA学习
date: 2023-04-11 12:38:53
tags:
---
## 1、注释、标识符、关键字、字面量

### 1.注释

单行注释：ctrl+/                     格式：//

多行注释：ctrl+shift+/           格式：/*  */

JavaDoc文档注释：                 格式：/**  */

### 2.标识符

java所有的组成部分都需要名字。类名、变量名以及方法名都被称为标识符。

**命名规范**

1.小驼峰命名法：(主要用于类)

规范一，标识符是一个单词的时候，所有字母小写       								  eg:name

规范二，标识符由多个单词组成的时候，从第二个单词开始，首字母大写   eg:firstName

2.大坨峰命名法：(主要用于类名)

规范一：标识符是由一个单词组成的时候，首字母大写          					    eg:Student

规范二：标识符是由多个单词组成的时候，每个首字母大写   					    eg:GoodStudent

### 3.关键字

**java当中被赋予特定涵义的单词**

|  abstract  |    assert    |   boolean   |     break     |    byte    |
| :--------: | :----------: | :---------: | :-----------: | :--------: |
|    case    |    catch     |    char     |     class     |   const    |
|  continue  |   default    |     do      |    double     |    else    |
|    enum    |   extends    |  **final**  |    finally    |   float    |
|    for     |     goto     |     if      |  implements   |   import   |
| instanceof |     int      |  interface  |     long      |   native   |
|    new     |   package    | **private** | **protected** | **public** |
|   return   |   strictfp   |    short    |    static     |   super    |
|   switch   | synchronized |    this     |     throw     |   throws   |
| transient  |     try      |    void     |   volatile    |   while    |

### 4.字面量

数据在程序中的书写格式

整数形式：

```java
public class test1 {
    /*
    main方法，又称为是主方法
    这里是程序的入口，如果没有编写主方法，程序不知道从哪里开始执行
    */
    public static void main(String[] args){
        System.out.println(18);
    }
}
```

小数形式：

```java
public class test1 {
    /*
    main方法，又称为是主方法
    这里是程序的入口，如果没有编写主方法，程序不知道从哪里开始执行
    */
    public static void main(String[] args){
        System.out.println(182.12);
    }
}
```

字符串数据：

```java
public class test1 {
    /*
    main方法，又称为是主方法
    这里是程序的入口，如果没有编写主方法，程序不知道从哪里开始执行
    */
    public static void main(String[] args){
        System.out.println("大家好！这是我的第一个java");
    }
}
```
