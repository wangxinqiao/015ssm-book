#  015ssm图书租赁管理系统
015ssm图书租赁管理系统


#### 介绍
IDEA/Eclipse开发环境，Spring,springMvc,Mybatis框架，前端Jsp技术，AJax技术，使用Mysql数据库。客户端的充值，使用的支付宝沙箱测试化境

数据导入：
在MySQL数据库中创建数据库，数据库名称建议为bookmanage(可自定义),导入book_management.sql及bm2.sql，注意sql导入必须为先book_management.sql后bm2.sql，否则会导致数据有误；

数据库相关配置：
数据库创建并导入完成后，在db.properties文件中配置数据库名称及用户名密码等；

smtp邮箱配置：
需要在system.properties中配置自己的smtp邮箱

redis安装：
需要在本地安装redis,安装成功后在MvcConfig中配置redis的地址和密码；

lombok插件安装：
本项目需要安装lombok插件，否则运行会有异常；

源码获取：[ **点此获取** ](http://www.shuyue.fun/index.php?type=productinfo&id=118)

## 注意事项：
1.项目启动后，在tomcat中配置项目路径必须要有项目名,前端需使用，如/bm2_war；
2.请使用Google浏览器，IE浏览器运行可能会有问题；

## 运行截图

![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/095000_baf67b29_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/095009_09868066_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/095017_38217e31_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/095026_bc1a4b80_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/095038_8f353fcc_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/095046_3f6fcadd_863230.png "屏幕截图.png")
