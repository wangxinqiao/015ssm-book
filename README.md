#  015ssm图书租赁管理系统
015ssm图书租赁管理系统

## 项目介绍
````
图书租赁管理系统，该系统分为管理员与普通读者两种角色；
管理员主要功能包括：
图书管理：添加、修改、删除；
图书分类管理：添加、修改、删除；
借阅信息：还书；
预定信息：确认借书；
归还信息；
统计管理：借书/归还、营业额、销量；
普通读者主要功能包括：预定图书、待拿图书、借阅中、归还信息等；
客户端的充值，使用的支付宝沙箱测试化境
````
演示视频：[ **点此查看** ](https://www.bilibili.com/video/BV1o44y1B7jL/)
源码获取：[ **点此获取** ](http://www.shuyue.fun/index.php?type=productinfo&id=118)

## 环境需要
````
1.运行环境：最好是java jdk 1.8，我们在这个平台上运行的。其他版本理论上也可以。
2.IDE环境：IDEA，Eclipse,Myeclipse都可以。推荐IDEA;
3.tomcat环境：Tomcat 7.x,8.x,9.x版本均可
4.硬件环境：windows 7/8/10 1G内存以上；或者 Mac OS；
5.是否Maven项目: 是；查看源码目录中是否包含pom.xml；若包含，则为maven项目，否则为非maven项目
6.数据库：MySql 8.0版本；
7.lombok插件安装：本项目需要安装lombok插件，否则运行会有异常；
````
## 技术栈
````
1. 后端：Spring SpringMVC MyBatis
2. 前端：JSP+bootstrap+jQuery+echarts
````
## 使用说明
````
1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并导入项目的sql文件；
2. 使用IDEA/Eclipse/MyEclipse导入项目，Eclipse/MyEclipse导入时，若为maven项目请选择maven;若为maven项目，导入成功后请执行maven clean;maven install命令，配置tomcat，然后运行；
3. 将项目中db.properties配置文件中的数据库配置改为自己的配置;
4. 运行项目，输入localhost:8080/bm/
````
## 运行截图

![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/095000_baf67b29_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/095009_09868066_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/095017_38217e31_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/095026_bc1a4b80_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/095038_8f353fcc_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/095046_3f6fcadd_863230.png "屏幕截图.png")
