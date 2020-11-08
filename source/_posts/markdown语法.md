---
title: markdown语法
date: 2020-11-08 16:25:36
tags:java后台学习笔记
---

### 标题

markdown支持如下的6级标题

```markdown
# 一级标题
## 二级标题
...
###### 六级标题
```

### 字体加粗

```markdown
**加粗**
```

### 字体倾斜

```markdown
*倾斜*
```

### 字体加粗并倾斜

```markdown
***加粗倾斜***
```

### 删除线

```markdown
~~~删除线~~~
```

### 引用

```markdown
> 引用的文字
```

### 分割线

```markdown
---
```

### 无序列表

```markdown
* 列表项1
* 列表项2
```

### 有序列表

```markdown
1. 列表项1
2. 列表项2
```

对于无序列表和有序列表来说都是可以嵌套使用的。

### 行内代码块

```markdown
`行内代码` 
```

对于行内代码块来说，是非常方便的，在写技术博客的时候如果提到某个方法或者是某个类，可以直接使用行内代码块，提高可读性。

### 多行代码块

~~~markdown
```多行代码块 多行代码块```
~~~

### 修改文字的颜色

我在使用富文本的时候经常有一些重点内容会让我标记成特殊的格式，在markdown中支持``标签，我们可以直接使用``标签来改变文字的一些样式

```markdown
<font face="黑体">我是黑体字</font>
<font face="微软雅黑">我是微软雅黑</font>
<font face="STCAIYUN">我是华文彩云</font>
<font color=red>我是红色</font>
<font color=#008000>我是绿色</font>
<font color=Blue>我是蓝色</font>
<font size=5>我是尺寸</font>
<font face="黑体" color=green size=5>我是黑体，绿色，尺寸为5</font>
```
