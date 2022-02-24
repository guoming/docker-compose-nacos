# Nacos
## 1、创建网络
``` SHELL
docker network create nacos
```
## 2、启动
``` SHELL
docker-compose up -d
```

## 3、配置数据库
https://github.com/alibaba/nacos/blob/develop/distribution/conf/nacos-mysql.sql

## 4、测试
http://localhost:8848/nacos/#/login
账号：nacos
密码：nacos