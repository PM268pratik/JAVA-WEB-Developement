 create table emp2(id int primary key,name varchar(100),email varchar(20),password varchar(20),salary float,permission varchar(20) default 'user' );
 insert into emp2 values(105,'Pratik','pm@gmail.com','pratik',400000.0,'admin');
 insert into emp2 values(108,'Raj','raj@gmail.com','Raj',50000.0,'user');
 insert into emp2 values(100,'Rahul','r@gmail.com','abcd',90000.0,'user');
 select * from emp2;
