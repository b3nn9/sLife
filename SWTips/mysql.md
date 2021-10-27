## MySQL
~~~
# service mysql restart
Restarting service MySQL 
Shutting down service MySQL                                          done
Creating MySQL privilege database... 
Installing MySQL system tables...
211027  7:19:27 [Note] /usr/sbin/mysqld (mysqld 5.5.43) starting as process 16488 ...
OK
Filling help tables...
211027  7:19:36 [Note] /usr/sbin/mysqld (mysqld 5.5.43) starting as process 16495 ...
OK

PLEASE REMEMBER TO SET A PASSWORD FOR THE MySQL root USER !
To do so, start the server, then issue the following commands:

/usr/bin/mysqladmin -u root password 'new-password'
/usr/bin/mysqladmin -u root -h UOS-MST password 'new-password'

Alternatively you can run:
/usr/bin/mysql_secure_installation

which will also give you the option of removing the test
databases and anonymous user created by default.  This is
strongly recommended for production servers.

See the manual for more instructions.

You can start the MySQL daemon with:
rcmysql start

You can test the MySQL daemon with mysql-test package

Please report any problems at http://bugs.mysql.com/

Starting service MySQL                                               done
UOS-MST:/var/lib/mysql # 
~~~
