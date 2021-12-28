---
title: 变大的红爱心
date: 2021-12-27
excerpt_separator: "<!--more-->"
categories:
     - SVG制作
tags:
  - svg
---

如何让自己的红色爱心桃变大呢？

<!--more-->

## 静态红色爱心桃

以下是我在[ **Font Awesome** ](https://fontawesome.com/)上找到的一个爱心桃，然后我将它的颜色改为了红色，就是下面的这个东西。

<svg width="10%" aria-hidden="true" color="red" focusable="false" data-prefix="fas" data-icon="heart" class="svg-inline--fa fa-heart fa-w-16" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path fill="currentColor" d="M462.3 62.6C407.5 15.9 326 24.3 275.7 76.2L256 96.5l-19.7-20.3C186.1 24.3 104.5 15.9 49.7 62.6c-62.8 53.6-66.1 149.8-9.9 207.9l193.5 199.8c12.5 12.9 32.8 12.9 45.3 0l193.5-199.8c56.3-58.1 53-154.3-9.8-207.9z"></path></svg>

## 放大的红色爱心桃

然后我给它加了这段代码：

![](/assets/images/SVG制作/huibiandadeaixin/变大的代码.png)

于是一个把鼠标放上去就会变大1倍的红色爱心桃就出现了.

<style>
 .redlove:hover{
width:200%;
transition:width 2s;
}

</style>
<div class="redlove">
<svg width="10%" aria-hidden="true" color="red" focusable="false" data-prefix="fas" data-icon="heart" class="svg-inline--fa fa-heart fa-w-16" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path fill="currentColor" d="M462.3 62.6C407.5 15.9 326 24.3 275.7 76.2L256 96.5l-19.7-20.3C186.1 24.3 104.5 15.9 49.7 62.6c-62.8 53.6-66.1 149.8-9.9 207.9l193.5 199.8c12.5 12.9 32.8 12.9 45.3 0l193.5-199.8c56.3-58.1 53-154.3-9.8-207.9z"></path></svg>
</div>