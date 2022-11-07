---
layout: post
title: 入手jekyll!
date: 2022-11-08 14:58:55
category: jekyll
tags: operation
---

jekyll使用技巧

### 博文链接

使用某篇文章的链接: [Getting-Started]{% post_url /jekyll/2022-11-07-Getting-Started %}
```
{% post_url 2010-07-21-name-of-post %}
``` 
使用子文件夹来组织的博文
```
{% post_url /subdir/2010-07-21-name-of-post %}
``` 
为你的文章生成超链接：
```
[Name of Link]({% post_url 2010-07-21-name-of-post %})
```