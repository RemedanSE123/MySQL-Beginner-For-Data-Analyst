
# MySQL-Beginner-For-Data-Analyst

This repository is designed for beginners in data analysis who want to practice and enhance their MySQL skills. MySQL is a powerful tool for querying and analyzing data, making it essential for data analysts. 

Here, you will find fundamental SQL queries and examples that cover the basics needed to work with databases, extract meaningful insights, and prepare data for analysis.

---


## Beginner SQL Commands

| **SQL Command** | **Description** |
|-----------------|-----------------|
| **SELECT**      | Retrieves data from one or more tables in the database. You can specify which columns to select or use `*` to select all columns. |
| **WHERE**       | Filters records that meet a specified condition. It helps you extract specific data by applying conditions to the columns. |
| **GROUP BY**    | Groups rows that have the same values in specified columns into aggregated data. It’s often used with aggregate functions like `SUM`, `COUNT`, `AVG`. |
| **ORDER BY**    | Sorts the results of a query in ascending (`ASC`) or descending (`DESC`) order based on one or more columns. |
| **HAVING**      | Filters records after an aggregation is performed. It is used with `GROUP BY` to specify conditions on the aggregated data. |
| **LIMIT**       | Limits the number of rows returned by a query, useful when you need a specific number of results. |
| **ALIAS**       | Temporarily renames a table or column for the purpose of a particular query. Aliases make the results more readable or help in complex queries. |





## Resources for Learning SQL

Here are some great resources for practicing and mastering SQL for data analysis. These include books, blogs, YouTube tutorials, online courses, practice sites, and cheat sheets to help you on your SQL learning journey.



### Cheat Sheets
- [SQL Basics Cheat Sheet](https://learnsql.com/blog/sql-basics-cheat-sheet/)
- [SQL Cheat Sheet by SQL Tutorial](https://www.sqltutorial.org/sql-cheat-sheet/)
- [SQL Basics Cheat Sheet by DataCamp](https://www.datacamp.com/)
- [SQL Commands Cheat Sheet – How to Learn SQL in 10 Minutes](https://blog.hubspot.com/website/sql-commands-cheat-sheet)
- [SQL Cheat Sheet for Newbies](https://intellipaat.com/)
- [SQL Commands Cheat Sheet by IntelliPaat](https://intellipaat.com/)
- [SQL Cheat Sheet by Mosh Hamedani](https://programmingwithmosh.com/)

---

These resources will help you build a strong foundation in SQL as a data analyst, providing both theory and practical exercises.



# SQL Exercises for Data Analysts (Beginner Level)

This repository contains **30 SQL exercises** based on the `employee_demographics` and `employee_salary` tables. These exercises cover key SQL concepts including **SELECT**, **WHERE**, **GROUP BY**, **ORDER BY**, **HAVING**, **LIMIT**, and **ALIAS**.

## Exercises

### 1. SELECT

1. Retrieve all the employee first names and ages.
2. Retrieve all the records from the employee_salary table.
3. Select all distinct occupations from the employee_salary table.

### 2. WHERE Clause

4. Find all employees who are older than 40 years.
5. Get the details of employees whose first name starts with 'A'.
6. Select employees with a salary greater than 60,000.

### 3. GROUP BY

7. Find the number of employees in each department.
8. Calculate the average salary in each department.
9. List the total number of employees by occupation.

### 4. ORDER BY

10. Retrieve all employee records and order them by their last names alphabetically.
11. Select all employees sorted by their salary in descending order.
12. Get the employees’ names and order them by their age from youngest to oldest.

### 5. HAVING

13. Find departments with more than 2 employees.
14. Show occupations where the average salary is above 50,000.
15. Retrieve departments with a total salary sum greater than 120,000.

### 6. LIMIT

16. Select the first 5 employees based on age.
17. Retrieve the top 3 highest-paid employees.
18. Select any 10 employees from the employee_demographics table.

### 7. ALIAS

19. Select employee first names with the alias Employee Name.
20. Get the employee salaries and rename the salary column to Income.
21. Show the department count using an alias Dept Count.

### 8. Complex Queries

22. Retrieve the names of employees older than 30, sorted by their salary in descending order.
23. Find the total salary of all employees in each department, but only for departments where the total salary exceeds 100,000.
24. Display the first name, last name, and occupation of all employees with a salary above 55,000, sorted by occupation.
25. Count the number of distinct departments.
26. Find the highest salary in the employee_salary table.
27. List employees along with their salaries where the salary is between 40,000 and 80,000.
28. Retrieve employees and their departments for those who have the job title 'Manager'.
29. Find the average age of employees in each department.
30. Get the total salary for employees whose first name contains the letter 'a'.

