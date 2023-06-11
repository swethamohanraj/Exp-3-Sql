# Exp_03_SQL-query-to-show-the-top-n-records-of-the-table-using-Limit-method
## AIM:
### To show the n number of given columns by uing the LIMIT method in SQL.
## ALGORITHM:
### STEP 1: Create a sample table in SQL using CREATE TABLE syntax
### STEP 2: Insert all the values and Titles respectively using INSERT INTO syntax
### STEP 3: Now check whether all the rows are affected or not by fetching the table
### STEP 4: After checking, now use SELECT for choosing the column name that we meant to sort and use FROM to choose the table
### STEP 5: Then use LIMIT syntax to limit the number of columns to be displyed as a result.
### STEP 6: After compiling and running the program, the results will be displayed.
## PROGRAM:
```
create table Employee(
  Sno int,
  Department varchar(50),
  No_of_workers int
);
insert into Employee (Sno,Department,No_of_workers)
values (1,'Development',15);
insert into Employee (Sno,Department,No_of_workers)
values (2,'Frontend Dv',10);
insert into Employee (Sno,Department,No_of_workers)
values (3,'Backend DV',7);
insert into Employee (Sno,Department,No_of_workers)
values (4,'Finance MM',8);
insert into Employee (Sno,Department,No_of_workers)
values (5,'Designer',12);
insert into Employee (Sno,Department,No_of_workers)
values (6,'Marketing',25);
insert into Employee (Sno,Department,No_of_workers)
values (7,'Chief heads',4);
insert into Employee (Sno,Department,No_of_workers)
values (8,'Law persuit',3);

select *from Employee
limit 5;
```

## OUTPUT:
![image](https://github.com/gpavithra673/Exp_03SQL-query-to-show-the-top-n-records-of-the-table-using-Limit-method/assets/93427264/088fd571-6424-484f-9a2e-e88dae155a98)
## RESULT:
### Thus we have successfully obtained the required result using the above-given code.
