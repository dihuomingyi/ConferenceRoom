# HBUConferenceRoom

#### 介绍

乐享会议————河北大学管理学院会议室预约系统  
为解决当前高校会议室预约效率低、资源冲突等问题，我们设计并开发了一款基于Java SSM框架的会议室预约系统——乐享会议。该系统采用了行业内广泛应用的前后端框架，运用AOC、IOP的思想，通过前后端分离开发的技术，打造了从web端全方位服务体系，是一款操作简单、功能齐全、安全稳定的会议室预约系统。

#### 功能

用户端：登录、会议室查询、会议室预约、管理我的预约、查看我的会议、查看当前会议室情况、查看通知公告、查看管理条例 等
管理员端：登录、会议室审核、邮件通知审核结果、会议室管理、用户管理、发布管理条例、发布通知公告、查看使用情况、查看数据统计 等  

#### 安装部署：

使用的编译工具有IDEA、navicat
环境是：apache-maven-3.5.3、jdk1.8.0_172、MySQL Server 5.7、Tomcat 8.0.9

#### 使用技术点：

语言：java
spring
springMVC: MVC框架
Tomcat: web容器
mybatis: ORM框架
bootstrap: css/html框架
JQuery: JS框架
MySQL: 关系型数据库
Logback: 日志框架
JUnit: 单元测试



#### 文件夹描述：路径为：ConferenceRoom

src中包含项目的全部代码，包括前后端和数据库相关的代码。
pom.xml文件是 Maven 工程的基本工作单元，是一个XML文件，包含了项目的基本信息，用于描述项目如何构建，声明项目依赖，等等。
其他均为项目配置所用到附属文件。
conferenceroom.sql:数据库文件

####
开发人员：刘思彤 1173080299@qq.com



web线上地址：

http://175.24.109.9:8080/front/frontlogin.html

http://175.24.109.9:8080/back/backlogin.html

