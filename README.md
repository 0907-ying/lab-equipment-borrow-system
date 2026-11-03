# 实验室设备借阅系统
O.5C JavaEE 最终项目，李鳌

## 引言
本系统用于管理实验室设备的借用与归还。

## 运行环境
- JDK 1.8
- Tomcat 9
- MySQL 5.7
- Maven 3.6及以上

## 部署步骤
1. git clone 克隆本项目到本地
2. 在MySQL中执行SQL脚本，新建数据库与数据表
3. 修改项目里的数据库连接配置
4. 使用Maven打包，把war包放入tomcat的webapps文件夹
5. 启动Tomcat，打开浏览器访问项目地址
