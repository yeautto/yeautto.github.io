---
layout: post
title: markdown 文档
date: 2022-11-6 14:58:55
---

**markdown** 文档的使用技巧

# 一、标题

##　使用 # 号标记
使用 # 号可表示 1-6 级标题，一级标题对应一个 # 号，二级标题对应两个 # 号，以此类推。

# 一级标题 
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

##　使用 = 和 - 标记一级和二级标题

我展示的是一级标题
=================

我展示的是二级标题
-----------------

# 二、段落
段落没有特殊的格式，直接编写文字就好，在段落后面使用一个空行来表示重新开始一个段落。

## 换行
换行是  
使用两个以上空格加上回车。

## 字体
*斜体文本* _斜体文本_  **粗体文本** __粗体文本__  ***粗斜体文本*** ___粗斜体文本___

##　分隔线
一行中用三个以上的星号、减号、底线来建立一个分隔线，行内不能有其他东西。你也可以在星号或是减号中间插入空格。　　
下面每种写法都可以建立分隔线：  

***
* * *
*****
- - -
----------

## 删除线
在文字的两端加上两个波浪线 ~~    ~~波浪线~~

## 下划线
通过 HTML 的 <u> 标签来实现    <u>带下划线文本</u>

## 脚注
脚注是对文本的补充说明。

创建脚注格式类似这样 [^123]。

[^123]:  这是一个脚注！！！

# 三、列表

## 无序列表
无序列表使用星号(*)、加号(+)或是减号(-)作为列表标记，这些标记后面要添加一个空格，然后再填写内容：

* 第一项
+ 第二项
+ 第三项
- 第一项
- 第二项
- 第三项

## 有序列表
有序列表使用数字并加上 . 号来表示，如：

1. 第一项
2. 第二项
3. 第三项

## 列表嵌套
只需在子列表中的选项前面添加两个或四个空格即可：

1. 第一项：
    - 第一项嵌套的第一个元素
    - 第一项嵌套的第二个元素
2. 第二项：
    - 第二项嵌套的第一个元素
    - 第二项嵌套的第二个元素
   
# 四、区块
区块引用是在段落开头使用 > 符号 ，然后后面紧跟一个空格符号：

> 区块引用  
> 学的不仅是技术更是梦想

## 区块嵌套
一个 > 符号是最外层，两个 > 符号是第一层嵌套，以此类推：

> 最外层
> > 第一层嵌套
> > > 第二层嵌套

## 区块中使用列表

> 区块中使用列表
> 1. 第一项
> 2. 第二项
> + 第一项
> + 第二项
> + 第三项

## 列表中使用区块

* 第一项
  > 第一项  
  > 第二项
* 第二项

# 五、代码
如果是段落上的一个函数或片段的代码可以用反引号把它包起来（`），例如：

`printf()` 函数

## 代码区块
代码区块使用 4 个空格或者一个制表符（Tab 键）。

    hello world {}

也可以用 ``` 包裹一段代码，并指定一种语言（也可以不指定）：

```javascript
$(document).ready(function () {
    alert('RUNOOB');
});
```

# 六、链接
格式：

[链接名称](链接地址) 或者 <链接地址>

例如：
这是一个链接 [博客](https://yeautto.github.io/) 或者 <https://yeautto.github.io/>

##　高级链接
这个链接用 1 作为网址变量 [baidu][1]
这个链接用 runoob 作为网址变量 [yeautoo][runoob]
然后在文档的结尾为变量赋值（网址）

[1]: https://www.baidu.com/
[runoob]: https://yeautto.github.io/

# 七、图片
语法格式如下：
```markdown
![alt 属性文本](图片地址)
![alt 属性文本](图片地址 "可选标题")
```
1.开头一个感叹号 !  
2.接着一个方括号，里面放上图片的替代文字  
3.接着一个普通括号，里面放上图片的网址，最后还可以用引号包住并加上选择性的 'title' 属性的文字  
你也可以像网址那样对图片网址使用变量

![龙 头像](https://pic.rmb.bdstatic.com/64b0c1d1fa7e98ab60bce7781f98749c.jpeg "图片title")

##　指定图片的高度与宽度
Markdown 还没有办法指定图片的高度与宽度，如果你需要的话，你可以使用普通的 <img> 标签。

<img decoding="async" src="https://pic.rmb.bdstatic.com/64b0c1d1fa7e98ab60bce7781f98749c.jpeg" width="100px">

# 八、表格

表格使用 | 来分隔不同的单元格，使用 - 来分隔表头和其他行。

|  表头   | 表头  |
|  ----  | ----  |
| 单元格  | 单元格 |
| 单元格  | 单元格 |

## 对齐方式

-: 设置内容和标题栏居右对齐。
:- 设置内容和标题栏居左对齐。
:-: 设置内容和标题栏居中对齐。

| 左对齐 | 右对齐 | 居中对齐 |
| :-----| ----: | :----: |
| 单元格 | 单元格 | 单元格 |
| 单元格 | 单元格 | 单元格 |

# 九、高级技巧

## 转义

Markdown 使用了很多特殊符号来表示特定的意义，如果需要显示特定的符号则需要使用转义字符，Markdown 使用反斜杠转义特殊字符： 

**文本加粗**  
\*\* 正常显示星号 \*\*

Markdown 支持以下这些符号前面加上反斜杠来帮助插入普通的符号：
```markdown
\   反斜线
`   反引号
*   星号 
_   下划线
{}  花括号
[]  方括号
()  小括号
#   井字号
+   加号
-   减号
.   英文句点
!   感叹号
```