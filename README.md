# -SSM-
2022级 软件工程毕业设计 
项目运行环境：JDK 1.8、Maven 3.6.3、MySQL 5.5.36
项目运行工具：IDEA 2021.3.1、Navicat for MySQL 11.1.13

部署说明：
①首先确保本机安装了MySQL 数据库，这里建议安装5.5.36版本的MySQL数据库。然后利用Navicat for MySQL 11.1.13数据库可视化工具在本机MySQL数据库中建立一个名为“floating”的数据库，最后在floating数据库中执行项目文件下的“floating.sql”文件，至此数据库建库建表工作结束；

②启动IDEA，需要提前配置好JDK1.8环境和Maven 3.6.3环境，配置方法在此不做过多阐述。在IDEA内以项目方式打开项目文件夹下的“floating”文件夹，等待IDEA对其进行Maven的解析与配置，解析与配置完成后便可启动项目以运行；

③启动任意一款浏览器，这里建议使用Google Chrome浏览器，在地址栏输入”http://localhost:8900/html/home/list.html”，按照页面提示输入用户名及密码。默认用户名密码表见如表1所示，至此项目成功部署运行。

表1 默认用户名和密码
系统角色	用户名	密码
系统管理员	admin	1234
基层防疫端	user	123456
管理部门端	manage	123456
