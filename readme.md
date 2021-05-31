# 简介以及markdown基本语法

一直想找个地方来写类似blog的东西，想过自己搭建wordpress--最后把时间全花在自定义主题上，想过在简书什么的地方写--总觉得国内的那些不安全，兜兜转转突然看到有人在github.io上写，我觉得蛮好的，但又懒得整这个，再之后看到有大神直接issue写，非常棒的主意，于是我把issue当作临时想法和踩坑的记录，然后一些相对长篇的内容整理归纳到repositry里。很多东西可能只是从别人那里复制过来，但为了能够让自己记住其中的东西，还是有必要自己归纳一下，以自己的口吻写下来，以后查阅也方便，记忆力有限，太多东西都是不用就马上忘记的。下面是Markdown基础语法，为了提示自己用的。。。

## 标题
`## 标题`（#数量表示标题层级即字体会慢慢变小，标题会自动附带换行，在github环境下，第一第二层标题还附带分割线）

普通行文中换行需要中间有一个空行

*这是斜体文字* `*这是斜体文字*`

**这是加粗文字** `**这是加粗文字**`

***这是加粗斜体文字*** `***这是加粗斜体文字***`（以上三个*可以用_替代）

~~这是删除线文字~~ `~~这是删除线文字~~`

>这是引用文字	(多个>可以指定多级引用） `>这是引用文字`

---
这是分割线 `---`

![图片alt](图片地址) `![图片alt](图片地址)`

[超链接名](超链接地址) `[超链接名](超链接地址)`

- 这是列表项目1 
    1. 子列表1
    2. 子列表2
- 这是列表项目2

```
- 这是列表项目1 
    1. 子列表1 （子列表前有4个空格）
    2. 子列表2
- 这是列表项目2
```

`单行代码`

```
代码块1
代码块2
```

表头表头表头|表头表头表头|表头表头表头
---|:--:|---:
内容|内容|内容
内容|内容|内容

```
表头表头表头|表头表头表头|表头表头表头
---|:--:|---:
内容|内容|内容
内容|内容|内容
```
第二行表示对齐方式 默认左对齐，:--:中间对齐，---:右对齐
