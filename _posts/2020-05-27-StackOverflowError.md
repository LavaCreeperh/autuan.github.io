---
layout:     post
title:      java.lang.StackOverflowError: null  错误
subtitle:   
date:       2020-05-27
author:     Autuan.Yu
header-img:
catalog: true
tags:
    - 错误记录
---

> 你做出了这个决定，这是你的代价.

## 错误
java.lang.StackOverflowError: null

## 原因
dubbo 不支持 LocalDateTime 类型

## 解决方法
更新dubbo方法 或转成字符串,在DAO层使用LocalDateTime.of()方法转回LocalDateTime

## PS
如果有更好的解决方法,欢迎留言.  

感激不尽