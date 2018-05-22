---
layout: post
title: 通过命令行执行mysql命令
---

有两种方法可以在命令行下执行sql命令。第一种是使用“-e“参数来指定需要执行的sql语句；第二种是通过管道的方式。语法及例子如下：
<pre>
1.
MYSQL_HOME/bin/mysql -u用户名 -p密码 -D数据库名 -e"sql 语句"
/usr/local/mysql/bin/mysql -uroot -p123456 -Dmysql -e"select host,user from user";

2.
echo "sql 语句" | MYSQL_HOME/bin/mysql -u用户名 -p密码 -D数据库名
echo "select host,user from user" | /usr/local/mysql/bin/mysql -uroot -p123456 -Dmysql
</pre>
