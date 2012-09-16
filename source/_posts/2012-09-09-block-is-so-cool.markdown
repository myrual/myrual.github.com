---
layout: post
title: "block_is_so_cool"
date: 2012-09-09 20:05
comments: true
categories: 
---
最近在异步编程的时候大量的使用了block，在设计异步处理的lib函数的时候也开始使用block。    
带来的好处是明显的： 

 *  设计lib函数的时候只需要确定自己的输入，输出，不用设计delegate，也不用迁就使用者设计特别的回调参数。
 *  使用lib函数的时候，所有的与这次调用相关的代码都在一个地方，不会分散在不同的位置。
 *  当某个业务需要多个异步处理才能完成的时候，代码逻辑异常的简单。
 
缺点：   

 *  block还是一个新概念，很多人不熟悉。
 *  写一个基于block的lib函数比基于run loop的麻烦很多，我总要翻翻apple的文档才写的出来。
 