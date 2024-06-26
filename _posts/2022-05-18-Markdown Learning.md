---
layout: post
title: "Markdown 每个开发者都应学的轻量级标记语言"
subtitle: "Markdown文件 程序员记笔记的正确方式"
author: "abin"
header-style: text
tags:
  - Markdown
  - 笔记
  - Typora
---

# Markdown Learning

## Markdown是什么

Markdown是一种轻量级标记语言，创始人为约翰·格鲁伯。它允许人们使用易读易写的纯文本格式编写文档，然后转换成有效的XHTML（或者HTML）文档。这种语言吸收了很多在电子邮件中已有的纯文本标记的特性。

由于Markdown的轻量化、易读易写特性，并且对于图片，图表、数学式都有支持，目前许多网站都广泛使用Markdown来撰写帮助文档或是用于论坛上发表消息。如GitHub、Reddit、Discord、Diaspora、Stack Exchange、OpenStreetMap 、SourceForge、简书等，甚至还能被用来撰写电子书。



### Markdown编辑器

Markdown编辑器有很多, up比较喜欢**Typora**这款编辑器, 支持实时预览.



**[Typora快捷键](https://www.cnblogs.com/hongdada/p/9776547.html)**



## 1.添加代码块

```java
//添加代码块
// ```java
// ```c

#include<iostream>
using namespace std;

class Shape{
	public:
		Shape(){cout<<"调用了Shape的构造函数"<<endl;}
		~Shape(){cout<<"调用了Shape的析构函数"<<endl;}	
		void GetArea(){}
};
```



```c
//C语言的代码块
// ```c 
#include "stdio.h"
```



```shell
#java -version
```



## 2.添加标题

```java
//标题语法

# 标题名称      一级标题
## 标题名称      二级标题
### 标题名称      三级标题
#### 标题名称      四级标题
##### 标题名称      五级标题
###### 标题名称      六级标题
    
    //下面是案例
```

# 标题名称      一级标题
## 标题名称      二级标题
### 标题名称      三级标题
#### 标题名称      四级标题
##### 标题名称      五级标题
###### 标题名称      六级标题







## 3.字体

```java
//加粗
**这是加粗的字体**
//代码高亮
==高亮的字体==
//删除线
~~删除线的字体~~
//斜体
 *斜体内容*
//加粗斜体
 ***加粗斜体***
```



**加粗的字体**

==高亮的字体==

~~删除线的字体~~

*斜体内容*

***斜体加粗内容***



## 4.引用

```java
//引用语法
>一级引用
>>二级引用
>>>三级引用
```

 

>一级引用
>>二级引用
>>
>>>三级引用





## 5.分割线

```c
//分割线1

---
    
//分割线2
 
***
    
```



//分割线1

---

//分割线2

***





## 6.图片的插入

```java
//语法
//在线图片或者本地图片

![图片的描述](图片的路径)
    
    //路径可以是本地路径,也可以是在线路径[在联网的情况下会显示]
```



![在线图片](https://scpic.chinaz.net/Files/pic/pic9/202107/hpic4212_s.jpg)







## 7.超链接

```java
//超链接基本语法
[我的GitHub](https://github.com/)
```

//超链接的使用

[我的GitHub](https://github.com/)





## 8.列表

```java
//列表语法
//无序列表
- 无序列表1
- 无序列表2
    
//有序列表
1. 有序列表1
```



- 无序列表1
- 无序列表2
- 

1. 序号1
2. 序号2





## 9.表格

```java
直接右键插入表格
    
```



| 头文件 | 列表 | 属性 |
| :----: | :--: | :--: |
|        |      |      |
|        |      |      |
|        |      |      |



## 10.行内代码

```c
//在代码的两端添加 ' 你的代码段 '
```





接下来的是一个行内代码: ` printf("hello world!");`hello Word!



