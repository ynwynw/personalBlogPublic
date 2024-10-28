## 本项目完整源码是收费的  接毕业设计和论文

### 作者微信：grapro666 QQ：3642795578 (支持部署调试、支持代做毕设)

### 接javaweb、python、小程序、H5、APP、各种管理系统、单片机、嵌入式等开发

### 选题+开题报告+任务书+程序定制+安装调试+论文+答辩ppt

**博客地址：
[https://blog.csdn.net/2303_76227485/article/details/143230727](https://blog.csdn.net/2303_76227485/article/details/143230727)**

**视频演示：
[https://www.bilibili.com/video/BV1iGyoYTEX6/](https://www.bilibili.com/video/BV1iGyoYTEX6/)**

**毕业设计所有选题地址：
[https://github.com/ynwynw/allProject](https://github.com/ynwynw/allProject)**

## 基于Java+Springboot+vue的个人博客管理系统(源代码+数据库+万字论文+开题+任务书)192

## 一、系统介绍
本项目前后端分离，分为用户、管理员两种角色，角色菜单可自行分配
### 1、用户：
- 注册、登录、博客浏览、评论、点赞、留言、博客发布、随笔发布、个人信息、密码修改

### 2、管理员：
- 数据统计、用户管理、角色管理、菜单管理、日志管理、文章管理、随笔管理、分类管理、标签管理、文章置顶、导出
- 留言管理、评论管理、留言管理、数据管理、服务管理、缓存管理

## 二、所用技术
后端技术栈：

- Springboot
- mybatis
- Mysql
- Maven
- Redis
- SpringSecurity
- Jwt

前端技术栈：

- Vue
- Vue-router
- axios
- elementUi
- echarts

## 三、环境介绍
基础环境 :IDEA/eclipse, JDK1.8, Mysql5.7及以上, Maven3.6, node14, navicat

所有项目以及源代码本人均调试运行无问题 可支持远程调试运行

## 四、页面截图
### 文档截图
![contents](./picture/picture0.png)
![contents](./picture/picture00.png)
![contents](./picture/picture000.png)
![contents](./picture/picture0000.png)
### 1、用户：
![contents](./picture/picture1.png)
![contents](./picture/picture2.png)
![contents](./picture/picture3.png)
![contents](./picture/picture4.png)
![contents](./picture/picture5.png)
![contents](./picture/picture6.png)
![contents](./picture/picture7.png)
![contents](./picture/picture8.png)
![contents](./picture/picture9.png)
![contents](./picture/picture10.png)
![contents](./picture/picture11.png)
![contents](./picture/picture12.png)
![contents](./picture/picture13.png)
![contents](./picture/picture14.png)
![contents](./picture/picture15.png)

### 2、管理员：
![contents](./picture/picture16.png)
![contents](./picture/picture17.png)
![contents](./picture/picture18.png)
![contents](./picture/picture19.png)
![contents](./picture/picture20.png)
![contents](./picture/picture21.png)
![contents](./picture/picture22.png)
![contents](./picture/picture23.png)
![contents](./picture/picture24.png)
![contents](./picture/picture25.png)
![contents](./picture/picture26.png)
![contents](./picture/picture27.png)
![contents](./picture/picture28.png)
![contents](./picture/picture29.png)
![contents](./picture/picture30.png)
![contents](./picture/picture31.png)
![contents](./picture/picture32.png)
![contents](./picture/picture33.png)

## 五、浏览地址

前台地址：http://localhost:8081

用户账号密码：liqiang/123456

后台地址：http://localhost:8082

管理员账户密码：admin/123456

## 六、部署教程
1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并执行项目的sql文件

2. 使用IDEA/Eclipse导入blog-server项目，若为maven项目请选择maven，等待依赖下载完成

3. 修改ruoyi-admin项目application.yml里面的文件路径配置和redis配置，application-druid.yml里面的数据库配置, 

4. 先启动redis然后src/main/java/com/ruoyi/RuoYiApplication.java启动后端项目

5. vscode或idea打开blog-ui前台项目

6. 在编译器中打开terminal，执行npm install 依赖下载完成后执行 npm run dev,执行成功后会显示访问地址


