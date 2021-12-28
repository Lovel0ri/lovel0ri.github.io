---
title: 在运动中变色的爱心
date: 2019-07-04
excerpt_separator: "<!--more-->"
categories:
     - SVG制作
tags:
  - svg
---

如何让一颗爱心在运动中变色呢？

<!--more-->

## 静态的爱心

以下是我在[ **Font Awesome** ](https://fontawesome.com/)上找到的一个爱心桃

<svg width="10%" aria-hidden="true" color="black" focusable="false" data-prefix="fas" data-icon="heart" class="svg-inline--fa fa-heart fa-w-16" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path fill="currentColor" d="M462.3 62.6C407.5 15.9 326 24.3 275.7 76.2L256 96.5l-19.7-20.3C186.1 24.3 104.5 15.9 49.7 62.6c-62.8 53.6-66.1 149.8-9.9 207.9l193.5 199.8c12.5 12.9 32.8 12.9 45.3 0l193.5-199.8c56.3-58.1 53-154.3-9.8-207.9z"></path></svg>

## 运动中的爱心

然后我再为它加了一段运动的代码，如图：

![](/assets/images/SVG制作/yundongzhongbianse/运动代码.png)

展示如下：

<style>
.like svg{
position: relative;
animation:deer 4s infinite;}			

@keyframes deer
{0%   {left:0px; top:0px;}
25%  {left:300px; top:0px;}
50%  {left:300px; top:300px;}
75%  {left:0px; top:300px;}
100% {left:0px; top:0px;}}
</style>

<div class="like">

<svg width="10%" aria-hidden="true" color="black" focusable="false" data-prefix="fas" data-icon="heart" class="svg-inline--fa fa-heart fa-w-16" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path fill="currentColor" d="M462.3 62.6C407.5 15.9 326 24.3 275.7 76.2L256 96.5l-19.7-20.3C186.1 24.3 104.5 15.9 49.7 62.6c-62.8 53.6-66.1 149.8-9.9 207.9l193.5 199.8c12.5 12.9 32.8 12.9 45.3 0l193.5-199.8c56.3-58.1 53-154.3-9.8-207.9z"></path></svg>

</div>

<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>

## 运动中变色的爱心

再然后我又在以上的基础再在它的运动代码中增加了颜色变化的代码：

![](/assets/images/SVG制作/yundongzhongbianse/运动中变色代码.png)

展示如下：

<style>
.love svg{
position: relative;
animation:deer 4s infinite;}			
			
@keyframes deer
{0%   {fill:black; left:0px; top:0px;}
25%  {fill:#00BFFF; left:300px; top:0px;}
50%  {fill:pink; left:300px; top:300px;}
75%  {fill:red; left:0px; top:300px;}
100% {fill:blavk; left:0px; top:0px;}}

</style>
<div class="love">
<svg width="10%" aria-hidden="true"  focusable="false" data-prefix="fas" data-icon="heart" class="svg-inline--fa fa-heart fa-w-16" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><path d="M462.3 62.6C407.5 15.9 326 24.3 275.7 76.2L256 96.5l-19.7-20.3C186.1 24.3 104.5 15.9 49.7 62.6c-62.8 53.6-66.1 149.8-9.9 207.9l193.5 199.8c12.5 12.9 32.8 12.9 45.3 0l193.5-199.8c56.3-58.1 53-154.3-9.8-207.9z"></path></svg>
</div>

<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>