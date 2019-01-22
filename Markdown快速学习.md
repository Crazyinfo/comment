---
title: Markdown快速学习
date: 2019-01-18 11:02:27
updated:
categories:
- 学习笔记
tags:
- Blog
---
搭建完博客后要用到Markdown标记语言写博客，可以生写Markdown，也可以借助一定的编辑器写。本文用到的是MarkdownPad2。
这篇文章仅描述了Markdown的基本书写规范，但也满足了书写博客的要求。
<!--more-->
## 标题(Atx形式)
1到6个#表示标题1到6阶

	##### 第五阶
	### 第三阶
还有Setext形式:

Setext 形式是用底线的形式，利用`=`（最高阶标题）和`-`（第二阶标题
## 区块
使用>来划分区块
> thies

> it is my blog

>写入时换行需要中间空一行

	> thies

	> it is my blog

	>写入时换行需要中间空一行
## 修辞和强调

	- *这是斜体*(将斜体内容头尾各一个*包起来)
	- _这是斜体_(将斜体内容头尾各一个_包起来)
	- **这是加粗**(将加粗内容头尾各两个*包起来)
	- __这是加粗__(将加粗内容头尾各两个_包起来)
- *这是斜体*
- _这是斜体_
- **这是加粗**
- __这是加粗__

## 列表
**无序列表**使用`*` `-` `+`三者均可

	* 你好
	- 你好
	+ 你好

* 你好
- 年后
+ 你好
- (`*` `-` `+`后跟一个空格再加内容，需要二级列表时`*``-``+`前再加四个空格或一个tap)

**有序列表**

	1. Bird
	2. McHale
	3. Parish
	8. 值得注意的是编写前面的序号不会影响输出
1. Bird
2. McHale
3. Parish
8. 值得注意的是编写前面的序号不会影响输出

## 分割线
------------------
在一行中用三个以上的`星号*`、`减号-`、`底线_`来建立一个分隔线，行内不能有其他东西。
******************

	* * *
	**********
	-----
	___________

## 链接
Markdown支持两种形式的链接语法：

**行内形式**：

This is my [Evey's Blog](http://crazyinfo.top/ "Title")

其中的`title`是可选择的，也可以不填，显示效果为鼠标触碰链接显示链接名

	This is my [Evey's Blog](http://crazyinfo.top/)

**参考形式**：

I get 10 times more traffic from [Google][1] than from
[Yahoo][2] or [MSN][3].

[1]: http://google.com/ "Google"
[2]: http://search.yahoo.com/ "Yahoo Search"
[3]: http://search.msn.com/ "MSN Search"
 
	I get 10 times more traffic from [Google][1] than from[Yahoo][2] or [MSN][3].

	[1]: http://google.com/ "Google"
	[2]: http://search.yahoo.com/ "Yahoo Search"
	[3]: http://search.msn.com/ "MSN Search"

**自动链接**
<http://crazyinfo.top/>

	http://crazyinfo.top/
## 图片
图片的语法和链接很像

**行内形式**：
![alt text](http://material.motimaster.com/momakeversion/george-desipris-1061591-unsplash.jpg "Title")

`title`是选择性的，显示效果依旧为鼠标触碰显示`title`的属性

`alt text`接着一个方括号，里面放上图片的替代文字

	![alt text](/path/to/img.jpg(或图片链接) "Title")

**参考形式**：
![alt text][id]

[id]: http://material.motimaster.com/momakeversion/1.jpg "Title"

	![alt text][id]

	[id]: /path/to/img.jpg(或图片链接) "Title"
## 代码
如果要标记一小段行内代码，你可以用反引号``(`)``把它包起来，例如：

Use the `printf()` function.

	Use the `printf()` function.
## 反斜杠
利用反斜杠来插入一些在语法中有其它意义的符号，例如：

\*literal asterisks\*

	\*literal asterisks\*

--------------------

参考链接<https://www.appinn.com/markdown/index.html>

这是[该文章文件地址](https://github.com/Crazyinfo/Blogbuilding/blob/master/Markdown%E5%BF%AB%E9%80%9F%E5%AD%A6%E4%B9%A0.md)