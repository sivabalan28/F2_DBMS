# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS
# Date
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
```create table student(rollno int,name char(20),age int,addr varchar(20),phoneno int);```

### OUTPUT:
![270737222-0a408222-71e9-489b-9a1c-e2018c96e9f2](https://github.com/sivabalan28/F2_DBMS/assets/113497347/77351b4a-be03-4a5c-9187-94332c64785d)

### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```alter table student add department char(30);```

### OUTPUT:
![270737487-d89fc1a6-0255-4e24-be57-d4a2bdbdb88e](https://github.com/sivabalan28/F2_DBMS/assets/113497347/3c1d0770-d533-4277-a141-ee852f6b67cd)


### 3) Drop the student table
 
### SQL QUERY: 
```drop table student;```

### OUTPUT:
![270737627-cda2e0c8-50d6-49e1-be64-1db873059e4c](https://github.com/sivabalan28/F2_DBMS/assets/113497347/e863e851-24b5-4797-a9b0-f71bb5abd50c)


### 4) Delete the student table using truncate keyword

### SQL QUERY: 
```truncate table student;```

### OUTPUT:
![270737740-321cfd54-fbd4-4ad7-800b-55ab4eda33e1](https://github.com/sivabalan28/F2_DBMS/assets/113497347/8fecf7f9-d939-4746-afca-18835053d963)


### 5) Rename the student table to mystudent

### SQL QUERY: 
```alter table student rename to mystudent;```

### OUTPUT:
![270737805-5c0207cf-d846-4bf2-a771-788ccaed64e5](https://github.com/sivabalan28/F2_DBMS/assets/113497347/9a049453-b770-4e49-b946-41929d5ac1f4)
