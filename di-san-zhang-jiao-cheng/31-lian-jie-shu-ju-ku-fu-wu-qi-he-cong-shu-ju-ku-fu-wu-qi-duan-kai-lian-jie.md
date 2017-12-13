
连接数据库的方式如下：
```
[root@sz www]# mysql -h 127.0.0.1 -u root -p
Enter password: 
```
参数说明：
- -h:运行数据库服务器的主机名
- -u:MySQL账号的用户名
- -p:提示输入MySQL账号的密码
看到'Enter password:'的提示后，输入MySQL账户密码即可。，结果如下：

```
[root@sz www]# mysql -h 127.0.0.1 -u root -p
Enter password: 
Welcome to the MySQL monitor.  Commands end with ; or \g.
Your MySQL connection id is 8170
Server version: 5.7.16-log Source distribution

Copyright (c) 2000, 2016, Oracle and/or its affiliates. All rights reserved.

Oracle is a registered trademark of Oracle Corporation and/or its
affiliates. Other names may be trademarks of their respective
owners.

Type 'help;' or '\h' for help. Type '\c' to clear the current input statement.

mysql> 

```

如果数据库服务器运行在本地，可以忽视主机相关参数：

```
[root@sz www]# mysql -u root -p 
Enter password: 
Welcome to the MySQL monitor.  Commands end with ; or \g.
Your MySQL connection id is 8171
Server version: 5.7.16-log Source distribution

Copyright (c) 2000, 2016, Oracle and/or its affiliates. All rights reserved.

Oracle is a registered trademark of Oracle Corporation and/or its
affiliates. Other names may be trademarks of their respective
owners.

Type 'help;' or '\h' for help. Type '\c' to clear the current input statement.

mysql> 

```