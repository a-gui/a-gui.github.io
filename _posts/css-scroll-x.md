---
title:  h5实现横向滚动的方法
layout: post
categories: CSS
tags: h5 css横向滚动
excerpt:
---
# css横向滚动


```css
/*横向滚动*/
.scroll-x{
  display: flex;
  flex-wrap: nowrap;
  overflow-x: auto;
}

//去除滚动条
&::-webkit-scrollbar {
	display: none;
}

//文字不换行
white-space: nowrap;
```