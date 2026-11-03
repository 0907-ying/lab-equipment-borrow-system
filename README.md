# 实验室设备借用系统
O.5C JavaEE课程大作业 李鳌

## 项目介绍
本系统是面向校园实验室的设备借用管理系统，支持设备信息管理、借用申请、归还审核。

## 环境要求
- JDK 1.8
- Tomcat 9
- MySQL 5.7
- Maven 3.6+

## 部署步骤
1. git clone 本项目到本地
2. 在MySQL中执行sql脚本，创建数据库和数据表
3. 修改项目中数据库连接配置
4. Maven打包，将war包放到tomcat的webapps目录
5. 启动Tomcat，浏览器访问项目地址
