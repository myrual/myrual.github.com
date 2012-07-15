---
layout: post
title: "go_lang_3_hour_tuto"
date: 2012-05-13 22:48
comments: true
categories: 
---
受[virshuo](http://www.v2ex.com/t/35526#reply16)的启发，我决定目前的项目不会启用erlang。因为我觉得说服别人学习FP是一件靠缘分的事情，难度太大了了。而说服别人学习一门语法和c语言差不多的语言还是相对容易的。所以今天花了一点时间开始学习go。    
印象：  
1. 正如很多人说的，go本身的语法内容很少。    
2. 把数据和操作数据的方法放在一起的手段与objective c非常相似。   
3. 命名方法也是推荐getter与变量名相同，setter使用setXyz的方式。   
4. 支持闭包。   
5. 没有while了，只有for。     
6. 大括号的位置很好，我真的很喜欢。 这一点上我追随[云风老师](http://blog.codingnow.com/2010/11/go_prime.html)。



------------------------
最终，连go也不用了，所有服务器通过http提供对外服务，这样所有的负载交给IIS或者Apache。
至于速度和性能，估计只能到时候再说。
真的会慢么？不一定。
