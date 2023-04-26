基于Springboot+html的前后端分离停车场管理系统

@[TOC](基于Springboot+html的前后端分离停车场管理系统)
# 项目简介
基于SpringBoot+html的前后端分离的停车场管理系统，本系统分为二种角色：管理员和收银员。

1．登录：管理员可以通过系统分配的账号登录系统中，收银员用户可以通过管理员登录系统后录入系统账号后登录系统。
2. 信息统计查看：管理员和收银员登录系统后在系统首页中可以通过图表清楚的看到停车场的收入营销情况，还能清楚的看到不同停车场的数据对比。
3. 订单管理：对进入各个停车场的车辆进行监控，车辆出入以及车辆是否月卡等进行收费以及相关的记录。
4. 停车场管理：对所有使用系统的小区或者其他地方的停车场进行管理，使用本系统后管理员和收银员可以通过系统管理所有的系统，方便进行统一管理。
5. 月卡管理：不同车辆不同小区可能会有不同的收费方式，月卡管理可以统一对所有使用本系统的地方进行月卡统一管理，不同月卡类型在进入时对应这不同的收费方式。
6. 用户管理：管理员可以在系统中录入相关的工作人员，也可以对相关工作人员进行数据管理，方便去管理系统中的所有的停车场。

管理员：
登录，数据统计查看，订单管理，停车场管理，月卡管理，用户管理

收银员：
登录，数据统计查看，订单管理，停车场管理，月卡管理

 # 项目获取
> [源码获取地址](http://www.manoncode.cn/details?id=100)

 
# 开发环境

运行环境：推荐jdk1.8；
开发工具：eclipse以及idea（推荐）、Hbuildx；
操作系统：windows 10 8G内存以上（其他windows以及macOS支持，但不推荐）；
浏览器：Firefox(推荐)、Google Chrome(推荐)、Edge;
数据库：MySQL8.0(推荐)及其他版本（支持，但容易异常尤其MySQL5.7（不含）以下版本）；
数据库可视化工具：Navicat Premium 15（推荐）以及其他Navicat版本
是否maven项目：是


 # 项目技术
 
后端：SpringBoot、Mybatis plus、mysql
前端：html、layui、jquery、ajax、echarts

 # 运行截图
 ![在这里插入图片描述](https://img-blog.csdnimg.cn/4bc3ddbe66a346ac84a163e016aba635.png#pic_center)
![在这里插入图片描述](https://img-blog.csdnimg.cn/0175b6bc228d448d90f94e83c6f01a87.png#pic_center)
![在这里插入图片描述](https://img-blog.csdnimg.cn/378e84f546404762b241c1c65f0d41a2.png#pic_center)
![在这里插入图片描述](https://img-blog.csdnimg.cn/15b0612d5e134953b1384a6340714385.png#pic_center)
![在这里插入图片描述](https://img-blog.csdnimg.cn/41a5c7edbfce43009682445c6a3caa31.png#pic_center)
![在这里插入图片描述](https://img-blog.csdnimg.cn/7813dccd45804797acea79c2b2a7cb81.png#pic_center)
![在这里插入图片描述](https://img-blog.csdnimg.cn/d0a7211ed2b443fe98e9d700078b8818.png#pic_center)
![在这里插入图片描述](https://img-blog.csdnimg.cn/dc1666093c064df88495d8c756fff045.png#pic_center)
![在这里插入图片描述](https://img-blog.csdnimg.cn/9386a736be96493e939a01f1d88307de.png#pic_center)
![在这里插入图片描述](https://img-blog.csdnimg.cn/cf655c0700e44eb784b684a415b118f2.png#pic_center)
![在这里插入图片描述](https://img-blog.csdnimg.cn/334c340447334eb399821c8a86486919.png#pic_center)
![在这里插入图片描述](https://img-blog.csdnimg.cn/f79bdfa3a30c4cdb8482dd4831f25ec8.png#pic_center)
![在这里插入图片描述](https://img-blog.csdnimg.cn/1965b27c9cf84f39b013463c51c9036b.png#pic_center)
![在这里插入图片描述](https://img-blog.csdnimg.cn/f04e1f0be14e4d35a437e639886bde8e.png#pic_center)

