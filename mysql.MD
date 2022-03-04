# wget https://repo.mysql.com/mysql80-community-release-el7-1.noarch.rpm
# yum localinstall mysql80-community-release-el7-1.noarch.rpm
# yum repolist enabled | grep "mysql.-community."
# rpm --import https://repo.mysql.com/RPM-GPG-KEY-mysql-2022
# yum install mysql-community-server
# yum-config-manager --disable mysql57-community
# yum-config-manager --enable mysql56-community
# service mysqld start
# systemctl enable mysqld.service
# systemctl status mysqld.service
# service mysqld status
# mysql --version
# mysql -u root -p
mysql>
# yum update mysql-server



show databases;
use databases;
create database databasename;
show tables;
create table tablename(columname datatype(size),columname datatype(size), ... nth columna datatype(size));

# example : 

studentinfo(
sno int(3),
sname varchar(10),
fname varchar(10),
dob date,
doj date,
class varchar(10));

desc tablename;

#insert command:

  insert into tablename ()values (value, value, value value);


    note: need not to use quotes for number format data types, 
    
    note: we should use quotes for char, varchar,date data types 

    for example:
      insert into studentinfo ()values (1,'ravi','sree','2000-12-01','2000-01-13','10th class');
#select * from tablename
   example: select * from studentinfo;





 