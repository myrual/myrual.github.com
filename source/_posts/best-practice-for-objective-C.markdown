---
layout: post
title: "Objective C 最佳实践"
date: 2012-04-03 19:46
comments: true
categories: 
---
原文在[此](http://ironwolf.dangerousgames.com/blog/archives/913)。  
只挑我认为重要的写下来。

***
**一直**  在实例的变量声明之前使用 @private， 而且  
**避免**  在类之外直接操作类的数据成员。  
为什么？  
 *   隐藏实现