# 006ssm药品管理系统
006ssm药品管理系统


## 1、本文介绍
该项目是前后台的医药管理系统（写在了一个web项目里），
简单明了，界面高端大气，共6张表，适合毕业设计使用，
后台管理系统用于药片的管理，
前台系统是用户购买药片，下订单使用。

源码获取： [**点此获取**](http://www.shuyue.fun/index.php?type=productinfo&id=104) 

## 2、配置环境
JDK 1.8
MYSQL 5.7
IDEA/Eclipse

## 3、功能
药品管理系统-后台：
订单管理
添加、编辑、删除
药品管理
添加、编辑、删除 - 药品名、药品类别、单价
药品类别管理
添加、编辑、删除 - 类别名称、描述
用户管理
添加、编辑、删除 - 用户名、电话、描述

药品商城-前台：
前台页面展示药品类别、药品缩略图、药品详情、可购买、加入购物车、形成订单

## 4、使用步骤
4.1 导入并执行sql文件 medicine_ms.sql,在db.properties中修改数据库相关配置，包括数据库名称、数据库用户名、密码等；
4.2 使用IDEA/Eclipse导入MedicinesMS项目
4.3 使用tomcat启动项目，我的项目名是/MedicinesMS(可自定义)
4.4 访问后台系统http://localhost:8080/MedicinesMS/admin_login.html
进入登录页面，用户名 admin,密码123
4.5 在后台系统上添加药品信息
4.6 访问前台页面http://localhost:8080/MedicinesMS/login.html,
使用用户名 admin,密码123登录，购买要求，形成订单。

## 运行截图
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/141428_290cca34_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/141439_4be11b08_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/141447_1c622816_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/141455_aef6a7c7_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/150724_c436aecb_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/150737_390a9251_863230.png "屏幕截图.png")

