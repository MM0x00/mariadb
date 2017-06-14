# mariadb 在线实验环境

## 软件简介

MariaDB是一个社区开发的MySQL关系数据库管理系统，旨在根据GNU GPL保持免费。作为领先的开源软件系统的一个分支，由于由于Oracle对其收购的担忧，MySQL的原始开发人员领先，因此，该公司是分支机构。贡献者必须与MariaDB基金会共享版权。

所属类别是数据库

特点：

与 MySQL 相比较，MariaDB 更强的地方在于：
- Maria 存储引擎
- PBXT 存储引擎
- XtraDB 存储引擎
- FederatedX 存储引擎
- 更快的复制查询处理
- 线程池
- 更少的警告和bug
- 运行速度更快
- 更多的 Extensions (More index parts, new startup options etc)
- 更好的功能测试
- 数据表消除
- 慢查询日志的扩展统计
- 支持对 Unicode 的排序

## 软件官网

https://mariadb.org/

## Dockerfile 使用方法

### 启动mariadb服务器实例
启动MariaDB实例很简单：
```
$ docker run --name some-mariadb -e MYSQL_ROOT_PASSWORD=my-secret-pw -d mariadb:tag
```
some-mariadb您要分配给容器的名称是要为my-secret-pwMySQL root用户设置的密码，是指定tag所需MySQL版本的标签

## 资源链接

- https://en.wikipedia.org/wiki/MariaDB
- https://hub.docker.com/_/mariadb/
