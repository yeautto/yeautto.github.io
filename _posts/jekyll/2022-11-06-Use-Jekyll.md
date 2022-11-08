---
layout: post
title: 博客格式
date: 2022-11-5 14:58:55
category: jekyll
tags: operation
---

 撰写博客

## 博客文件夹

_posts 文件夹存放的就是 博客文章。

### 创建文章的文件

发表一篇新文章，你所需要做的就是在 _posts 文件夹中创建一个新的文件。

文件名的命名非常重要。文件格式： 

> xxxx-xx-xx-标题.md

### 内容格式

所有博客文章顶部必须有一段 YAML 头信息(YAML front- matter)。

> layout: post
> title: 标题!


## 链接

使用某篇文章的链接: [Hello-World]({% post_url 1997-03-18-Read-Me %})

使用子文件夹来组织的博文: [Getting-Started]({% post_url /jekyll/2022-11-06-Use-Jekyll %})

为你的文章生成超链接：[Name of Link]({% post_url 1997-03-18-Read-Me %})

## 图片

![404]({{ site.baseurl }}/images/404.jpg)
