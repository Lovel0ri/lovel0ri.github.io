---
layout: page
title: box-shadow 盒阴影，为你的边框蒙上一层“薄纱”
date: 2021-12-25

---------

box-shadow是一种CSS3高级技术，十分适合响应式，现在就让我来带你们走近盒阴影，制作出属于自己的美观的“盒子”吧

## 课本《响应式Web设计 HTML5和CSS3实战》中关于盒阴影的描写：

盒阴影容许你在元素的内部或者外部创建盒状的阴影效果。

```
.shadow{
    box-shadow: 0px 3px 5px #444:
}
```

它的语法包括：水平偏移值（h-shadow)、垂直偏移值(v-shadow)、模糊距离(blur)、阴影尺寸(spread)、阴影颜色(color)，还有将外部阴影改为内部阴影的值(inset),其中水平距离跟垂直糊距离是必须值。

## 定义和用法：

一般想添加盒阴影都是在向div元素添加box-shadow，下面就让我来展示一下，我曾经修改的作品中的一些关于盒阴影的：

- 首先是在导航栏的盒阴影设置：这个地方首先是添加了div元素对nav定义
- 然后就是在css样式文件夹中在nav中添加box-shadow，然后进行修改
- 同样也是先在index.html中对页面布局中的container进行div定义，然后就是在css样式文件夹中在container中添加box-shadow

## 