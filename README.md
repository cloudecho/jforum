# 开发环境
开发时数据库配置（MySQL）：/WebRoot/WEB-INF/config/database/mysql/mysql.properties

# 安装
1、创建MySQL数据库
```
CREATE DATABASE jforum DEFAULT CHARACTER SET utf8 COLLATE utf8_bin;
grant all on jforum.* to jforum@'%' identified by 'jforum';
grant all on jforum.* to jforum@'localhost' identified by 'jforum';
```

2、在线安装
将程序打包为jforum.war部署至tomcat，访问
```
http://localhost:8080/jforum/install.jsp
```