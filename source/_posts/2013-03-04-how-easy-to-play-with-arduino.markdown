---
layout: post
title: "how easy to play with arduino"
date: 2013-03-04 22:42
comments: true
categories: 
---
###万事俱备，只欠代码
arduino以及各种配件终于在今天全都到齐了。官方支持mac真是好啊，插usb就能用，第一个闪灯的demo一次运行成功。顺利的超乎我的想象。

用光敏电阻，探测了一下室内的光强，果然可以知道光的强弱，看来能作点有意思的东西了。下一步就是把rf模块在raspberry和arduino两头都转起来就并且联系上就可以了。

###TODO
1.  让arduino把rf模块驱动起来。预计2天。
2.  让raspberry把rf模块驱动起来。预计1周。
3.  两个模块可以对着发送数据。预计1周。
4.  网站实时获取传感器信息，预计1天。


###Why issue management matter
这一阵用bitbucket的issue来驱动我的日常开发。具体流程很简单，

*  定义任务：比如fix bug,或者实现新功能，任务定义应该满足：少写代码，快速验证效果。
*  去issue系统上新建一个issue，bugfix自然选 bug，新功能可以选proposal或者task，系统自动分配一个issue id。然后指派给我自己。
*  只针对单一的issue做开发，测试完毕后直接commit 代码，commit消息中 fix #issueid就可以了，系统自动把issue关掉.

好处： 
*  成就感很高，看着issue id快速爬升
*  任务如何完成可追溯。

###So
自己的项目必须用issue管理。另外bitbucket的服务真心不贵。

