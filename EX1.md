# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS

## AIM:
To create a student database and execute DDL queries using SQL.


## DDL (Data Definition Language)
<div align="justify">
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.
</div>
 
## List of DDL commands: 
<div align="justify">
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
DROP: This command is used to delete objects from the database.
ALTER: This is used to alter the structure of the database.
TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.
RENAME: This is used to rename an object existing in the database.
</div>

## Query:
### 1) Create a table student with the following fieds rollno,name,age,address,phoneno.

### SQL QUERY: 

create table student(rollno int,name char(20),age int,addr varchar(20),phoneno int);

### OUTPUT:

![image](https://github.com/Dineshkarthick27/G2_DBMS/assets/120552008/a01ff0bd-f38a-4bbb-8c5e-0f1dc68a7afe)

### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
alter table student add department char(30);
### OUTPUT:

![image](https://github.com/Dineshkarthick27/G2_DBMS/assets/120552008/d7e2b771-db1a-4bdb-9a66-a4366d43a70b)

### 3) Drop the student table
 
### SQL QUERY: 
drop table student;

### OUTPUT:
![image](https://github.com/Dineshkarthick27/G2_DBMS/assets/120552008/4a5f5da8-baf3-4ed8-b9fc-64d0fe333aed)


### 4) Delete the student table using truncate keyword

### SQL QUERY: 
truncate table student;

### OUTPUT:

![image](https://github.com/Dineshkarthick27/G2_DBMS/assets/120552008/9e8188de-b15e-4ead-b9d1-f27871d3b77f)


### 5) Rename the student table to mystudent

### SQL QUERY: 
alter table student rename to mystudent;

### OUTPUT:
![image](https://github.com/Augustine0306/G2_DBMS/assets/119404460/7d6d43b7-4e63-4992-a1c3-79a612bbd0e3)
