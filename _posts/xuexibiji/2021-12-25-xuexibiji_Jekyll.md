---
layout: page
title: Jekyll文件夹的基本结构课堂笔记
date: 2021-12-24

categories:
     - 学习笔记
---

在我看来Jekyll文件夹是一个命名很有趣的文件夹，不仅命名有趣，他的每个文件夹都有自己独特的含义而且内容也都是很符合文件名的，让人搜索信息时总是很方便。

<!--more-->

## Jekyll文件夹结构

这堂课跟我们的期末项目其实是有关系的，因为期末项目就是在一个Jekyll文件夹里修改，自定义的。还记得赵老师讲过的比较重要的文件夹：

* _layout文件夹，这是一个存放各种网页模板的文件夹，像主页，列表页，博客内容页面，这些分别的页面模板都是放在这里的。

![](..\..\images\xuexibiji\xuexibiji-layouts.jpg)

* _config.yml文件夹，这是全网站通用设置保存的地方，比如网站主题，名称，介绍，域名，Github用户名等。.yml是像.ini一样的配置文件类型。

![](..\..\images\xuexibiji\xuexibiji-config.jpg)

* 还有其他像css文件夹，_includes文件夹，_posts文件夹等都有各自特定的意义。

![](..\..\images\xuexibiji\xuexibiji-css.jpg)



## Front-Matter文件头信息

它是写在每个Markdown文件头部的设置信息，主要是指明这篇文章标题、日期、使用的模板、样式、标签、分类等，这样Jekyll就可以根据这些设置把markdown文件转换成你想要的最终HTML网页了。以下是它的基本格式：

```
---
layout: post
title: "Welcome to Jekyll!"
date: 2021-12-25 21:05:17
categorier: jekyll update
---
```

![](..\..\images\xuexibiji\xuexibiji-文件头信息.jpg)

## 头信息的常用参数

- layout: 指明模板名称，即指定使用_layout文件夹中的哪个HTML网页做为模板。
- title: 这篇文章的标题。
- date: 这篇文章的日期。
- categories: 这篇文章的分类。

## 感想

通过老师的讲解，我明白了Jekyll的每个文件夹都有他特定的意义，每个文件夹的命名也是有深意的，对于日后的维护都是十分方便的，减少更新文章内容带来多余的不必要的操作。从此也可以看出这门课程的博大精深之处。