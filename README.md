# weiyi61
基于流媒体技术的视频网站设计与实现

#### 介绍
本文基于流媒体技术，使用Java为主要开发语言，从网站后台到Web与Android客户端，实现一个比较完整的视频网站。本视频网站主要涉及的技术包含JavaEE、流媒体和Android等。这些技术之中的重中之重是流媒体服务器的搭建，而开源项目Nginx已经为搭建高性能流媒体服务器提供了很好的实现。所以项目的主要内容转移到了视频文件与内容的管理上面。使用Spring来整合Spring MVC和Mybatis完成服务器端的软件开发，利用Spring的Ioc特性来装配和管理JavaBean，利用Spring MVC来做请求的分发与处理，利用Mybatis来做数据访问，从而完成服务器端的应用开发。客户端方面，使用JSON作为数据交换格式，与服务器端进行通信，然后为用户展示数据。
本视频网站由于受某些条件的限制，存在几点明显的不足。第一，缺少高可用支持，不支持集群部署。第二，视频文件类型支持单一，没有转码服务。第三，不对外开放用户系统。若此后有机会并有条件支持，可继续完善。


![输入图片说明](https://images.gitee.com/uploads/images/2020/1129/195317_72787cdf_4865385.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2020/1129/195336_e98b6fe8_4865385.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2020/1129/195350_f4df4474_4865385.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2020/1129/195357_36504bcd_4865385.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2020/1129/195405_6033da5d_4865385.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2020/1129/195416_3ad42bfb_4865385.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2020/1129/195427_ac9816ac_4865385.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2020/1129/195440_e7bed9e1_4865385.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2020/1129/195451_a7d0d554_4865385.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2020/1129/195501_33f24cf1_4865385.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2020/1129/195520_b92db775_4865385.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2020/1129/195528_b09637d0_4865385.png "屏幕截图.png")


联系Q：2762501186
![输入图片说明](https://images.gitee.com/uploads/images/2020/1119/003728_cd598bb9_4865385.jpeg "微信.jpg")
