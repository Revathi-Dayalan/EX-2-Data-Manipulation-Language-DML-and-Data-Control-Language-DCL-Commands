# EX 2 Data Manipulation Language (DML) Commands and built in functions in SQL
## AIM:
To create a manager database and execute DML queries using SQL.


## DML(Data Manipulation Language)
<div align="justify">
The SQL commands that deal with the manipulation of data present in the database belong to DML or Data Manipulation Language and this includes most of the SQL statements. It is the component of the SQL statement that controls access to data and to the database. Basically, DCL statements are grouped with DML statements.
</div>

## List of DML commands: 
<div align="justify">
INSERT: It is used to insert data into a table.<br>
UPDATE: It is used to update existing data within a table.<br>
DELETE: It is used to delete records from a database table.<br>
</div>

## Create the table as given below:
```sql
create table manager(enumber number(6),ename char(15),salary number(5),commission number(4),annualsalary number(7),Hiredate date,designation char(10),deptno number(2),reporting char(10));
```
## insert the following values into the table
```sql
insert into manager values(7369,'Dharsan',2500,500,30000,'30-June-81','clerk',10,'John');
insert into manager values(7839,'Subu',3000,400,36000,'1-Jul-82','manager',null,'James');
insert into manager values(7934,'Aadhi',3500,300,42000,'1-May-82','manager',30,NULL);
insert into manager values(7788,'Vikash',4000,0,48000,'12-Aug-82','clerk',50,'Bond');
```

### Q1) Update all the records of manager table by increasing 10% of their salary as bonus.

### QUERY:

![image](https://github.com/Revathi-Dayalan/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/96000574/b1005d8d-62e4-4bab-9f3f-451998a2b17c)


### OUTPUT:

![image](https://github.com/Revathi-Dayalan/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/96000574/003cbb16-7ec9-43fc-9635-ad71836acb22)


### Q2) Delete the records from manager table where the salary less than 2750.


### QUERY:

![image](https://github.com/Revathi-Dayalan/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/96000574/41f54580-516d-4550-b6be-ac1428d2a53f)



### OUTPUT:

![image](https://github.com/Revathi-Dayalan/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/96000574/e41f0eec-738f-4b2a-b0d7-5e1da923ee49)


### Q3) Display each name of the employee as “Name” and annual salary as “Annual Salary” (Note: Salary in emp table is the monthly salary)


### QUERY:

![image](https://github.com/Revathi-Dayalan/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/96000574/575c0720-d3fd-4c40-ad44-8c56f5bb2916)



### OUTPUT:

![image](https://github.com/Revathi-Dayalan/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/96000574/d185750a-7fea-43cb-9229-f7631c2ecd2f)


### Q4)	List the names of Clerks from emp table.


### QUERY:

![image](https://github.com/Revathi-Dayalan/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/96000574/47fe0755-f97a-444c-a2f2-6d51d4cf13b5)



### OUTPUT:

![image](https://github.com/Revathi-Dayalan/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/96000574/b1149677-aa68-48c9-933a-5e7ad4303358)



### Q5)	List the names of employee who are not Managers.


### QUERY:

![image](https://github.com/Revathi-Dayalan/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/96000574/46fb0096-af51-4984-9922-f8b9f6ca4f64)



### OUTPUT:

![image](https://github.com/Revathi-Dayalan/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/96000574/869f6931-2652-4269-9495-aebfcfbd074a)



### Q6)	List the names of employees not eligible for commission.


### QUERY:

![image](https://github.com/Revathi-Dayalan/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/96000574/fdac5fdc-76ec-4f40-854e-b0f12f859dde)



### OUTPUT:

![image](https://github.com/Revathi-Dayalan/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/96000574/27ad1abd-17a7-4abf-a698-6d3925899897)



### Q7)	List employees whose name either start or end with ‘s’.


### QUERY:

![image](https://github.com/Revathi-Dayalan/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/96000574/ada83313-0342-4232-8309-888e71772d91)


### OUTPUT:

![image](https://github.com/Revathi-Dayalan/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/96000574/0729da2e-257b-451f-86e8-88814424cf9f)



### Q8) Sort emp table in ascending order by hire-date and list ename, job, deptno and hire-date.


### QUERY:

![image](https://github.com/Revathi-Dayalan/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/96000574/302304ce-76a4-401b-a8a7-e2a8cfd1f4f1)



### OUTPUT:

![image](https://github.com/Revathi-Dayalan/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/96000574/e304552f-b760-4583-a502-4075ac54c75c)



### Q9) List the Details of Employees who have joined before 30 Sept 81.


### QUERY:

![image](https://github.com/Revathi-Dayalan/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/96000574/95a44ade-eafa-41bd-b8a8-355d4df2d6af)



### OUTPUT:

![image](https://github.com/Revathi-Dayalan/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/96000574/75c2578b-4b2c-4780-8b5b-7f49fb71f177)



### Q10)	List ename, deptno and sal after sorting emp table in ascending order by deptno and then descending order by sal.


### QUERY:

![image](https://github.com/Revathi-Dayalan/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/96000574/dbbff1c4-bcd2-45a1-817e-924c751510b0)



### OUTPUT:

![image](https://github.com/Revathi-Dayalan/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/96000574/da89d592-d4cb-43ac-bf95-a38470d23b0d)



### Q11) List the names of employees not belonging to dept no 30,40 & 10


### QUERY:

![image](https://github.com/Revathi-Dayalan/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/96000574/704077d2-fba9-4a44-90b2-3d8233581943)


### OUTPUT:

![image](https://github.com/Revathi-Dayalan/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/96000574/95d2f8af-018f-4634-99f9-5fb0afab2586)


### Q12) Find number of rows in the table EMP

### QUERY:

![image](https://github.com/Revathi-Dayalan/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/96000574/5aed668c-8327-4dcf-bd9b-c5e8c2a0fe82)


### OUTPUT:


![image](https://github.com/Revathi-Dayalan/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/96000574/db605bdb-4fe5-4cac-897f-8b2c7356ae00)


### Q13) Find maximum, minimum and average salary in EMP table.

### QUERY:

![image](https://github.com/Revathi-Dayalan/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/96000574/8343f2ab-78b2-46e7-b32d-83dd68cfde2e)



### OUTPUT:



![image](https://github.com/Revathi-Dayalan/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/96000574/d86b02c7-2257-43c0-a172-20a151c4e4d9)

### Q14) List the jobs and number of employees in each job. The result should be in the descending order of the number of employees.

### QUERY:

![image](https://github.com/Revathi-Dayalan/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/96000574/70a80a4e-0c8a-4c31-8e5f-95843a52cc33)



### OUTPUT:

![image](https://github.com/Revathi-Dayalan/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/96000574/58b51158-7f4c-48d8-b8f5-564b3cb7fe77)


## RESULT:
Thus the  Data Manipulation Language (DML) Commands and built in functions in SQL
