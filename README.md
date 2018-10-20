# 蘑菇博客

#### 项目介绍
个人学习用的博客项目，前台使用Vue +Element , 后端使用spring boot + spring cloud + mybatis-plus进行开发

- 从大学的时候开始，就一直想要搭建一套属于自己的博客系统，但是一直被没有去弄，现在时间多了，结合自己的技术栈，使用前后端分离架构进行项目的开发，也希望自己能够将项目一步步进行完善。
- 现在挺多是SSM或者SSH的博客管理系统，现在我想用spring boot + spring cloud  + vue 的微服务架构
- 由于原来做过vue + element-ui 做过管理系统，所以现在打算做一套自己的、基于当前最新技术栈、前后端分离的微服务博客系统。

#### 项目介绍

- MoguBlog 是一款基于最新技术开发的多人在线、简洁的博客系统；
- mogu_admin: 是admin端API接口服务；
- mogu_web: 是web端API接口服务；
- mogu_eureka: 服务发现服务器；
- mogu_picture: 图片服务器，用于图片上传和下载；
- mogu_utils: 是常用工具类；
- mogu_xo: 是存放 Entity，Service，Dao层的
- mogu_base: 是一些Base基类
- mogu_config: 是存放一些配置
- doc: 是蘑菇博客的一些文档和数据库文件
- 该博客系统的前端页面代码见 vue_mogu_admin  和 vue_mogu_web

#### 技术架构

- 后端采用的技术：SpringBoot、Spring cloud 、MyBatis-Plus、Spring Security + JWT、Solr, Redis , Mysql , Nginx , Swagger
- 前端采用的技术： Vue， Element， ES6， CKEditor

#### 项目特点

- 友好的代码结构及注释，便于阅读及二次开发
- 实现前后端分离，通过Json进行数据交互，前端再也不用关注后端技术
- 页面交互使用Vue2.x，极大的提高了开发效率
- 引入swagger文档支持，方便编写API接口文档

#### 致谢

- 感谢杨青小姐姐的博客模板，http://www.yangqq.com/
- Vue项目参考这篇博客：https://segmentfault.com/a/1190000009506097
- 感谢苞米豆提供的Mybatis-plus框架：http://mp.baomidou.com/

#### 相关截图

- ### admin端

  ![image text](E:\study_work_space\mywork6\UploadImage\mogublog\admin\login.png)

  ![image text](E:\study_work_space\mywork6\UploadImage\mogublog\admin\bashboard.png)

  ![image text](E:\study_work_space\mywork6\UploadImage\mogublog\admin\blog.png)

  ![image text](E:\study_work_space\mywork6\UploadImage\mogublog\admin\blogEdit.png)

  ![image text](E:\study_work_space\mywork6\UploadImage\mogublog\admin\addPicture.png)

  ![image text](E:\study_work_space\mywork6\UploadImage\mogublog\admin\blogSort.png)

  ![image text](E:\study_work_space\mywork6\UploadImage\mogublog\admin\solrIndex.png)

  ![image text](E:\study_work_space\mywork6\UploadImage\mogublog\admin\swagger.png)



- Web端

  ![image text](E:\study_work_space\mywork6\UploadImage\mogublog\web\index.png)

  ![image text](E:\study_work_space\mywork6\UploadImage\mogublog\web\index2.png)

  ![image text](E:\study_work_space\mywork6\UploadImage\mogublog\web\about.png)

  ![image text](E:\study_work_space\mywork6\UploadImage\mogublog\web\time.png)

