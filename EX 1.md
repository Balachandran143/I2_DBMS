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
```
 CREATE TABLE STUDENTT(rollno INT PRIMARY KEY,name1 VARCHAR(255),age INT,address VARCHAR(255),phoneno VARCHAR(15));
```


### OUTPUT:
![Screenshot 2023-09-09 141950](https://github.com/Balachandran143/I2_DBMS/assets/118886489/d8dda071-0f23-48e9-a8ba-6c2b89540435)

### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```
ALTER TABLE STUDENT2 ADD dept VARCHAR(50);
```
### OUTPUT:
![Screenshot 2023-09-09 142415](https://github.com/Balachandran143/I2_DBMS/assets/118886489/c0c7e6f0-4103-447b-b5a1-174a354103e8)


### 3) Drop the student table
 
### SQL QUERY: 
```
drop table student3;
```

### OUTPUT:
![Screenshot 2023-09-09 142532](https://github.com/Balachandran143/I2_DBMS/assets/118886489/2b0afc98-2503-415e-808c-dafe0dced992)


### 4) Delete the student table using truncate keyword

### SQL QUERY: 
```
truncate table student3;
```
### OUTPUT:
![Screenshot 2023-09-09 142732](https://github.com/Balachandran143/I2_DBMS/assets/118886489/ce3a2b1a-d160-47b2-9254-7b64c30fe9b1)


### 5) Rename the student table to mystudent

### SQL QUERY: 
```
alter table student2 rename to student3;
```
### OUTPUT:
![Screenshot 2023-09-09 142912](https://github.com/Balachandran143/I2_DBMS/assets/118886489/9f4c56ed-b069-4cd7-b65e-b6f3cf284dd6)
