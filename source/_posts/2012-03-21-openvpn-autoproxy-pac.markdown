---
layout: post
title: "autoproxy with vpn"
date: 2012-03-21 21:54
comments: true
categories: 
---
有vpn的情况下，对部分网站使用vpn，部分不用。
在openpvn的配置文件里面，找到"redirect-gateway def1"，在这行前面加上#  
正常连接VPN  
在你的浏览器中使用10.13.0.1:3128作为http和https代理使用。mac上可以安装firefox。  
如果以上步骤可以工作，那么去 https://autoproxy2pac.appspot.com/ 下载一个pac文件，记得把代理工具那里选其他，服务器选http 10.13.0.1  端口 3128  
然后在mac里面使用这个pac文件就行了。  
现在，youku，菲斯不可，特维特，qq，微薄都可以找到自己的快速通道了.