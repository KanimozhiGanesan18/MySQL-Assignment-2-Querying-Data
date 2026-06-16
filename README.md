# MySQL-Assignment-2-Querying-Data
As a Data Analyst, the company requires an Employee Database to store and manage information  related to employees, departments, and locations within the organization.   You are required to design and manage this employee database using MySQL DDL commands,  focusing on creating, modifying, and managing to ensure data integrity and consistency.


Dataset Description : 

You will work to create the following three tables: 

● Table: Department  

Attributes: 
○ department_id – Primary Key 
○ department_name 

● Table: Location  

Attributes: 

○ location_id – Primary Key 
○ location_name 

● Table: Employees  

Attributes: 

○ employee_id – Primary Key 
○ Employee_name 
○ Gender 
○ Age 
○ Hire_date 
○ Designation 
○ Salary 
○ department_id – Foreign Key referencing department(department_id) 
○ location_id – Foreign Key referencing location(location_id) 
Tasks 

Clause & Operators: 

1. DISTINCT VALUES:  

*  A query to retrieve distinct salaries from the Employees table.  

2. ALIAS (AS):  

*  Provide aliases for the "age" and "salary" columns as "Employee_Age" and 
"Employee_Salary", respectively.  

3. WHERE CLAUSE & OPERATORS:  

*  Retrieve employees with a salary greater than ₹50000 and hired before 
2016-01-01.  
*  Find the employee whose designation is missing and fill it with "Data 
Scientist".  

Sorting and Grouping Data:  

1. ORDER BY:  

● Find employees sorted by department ID in ascending order and salary in 
descending order.  

2. LIMIT:  

● Display the first 5 employees hired in the year 2018. 

3. AGGREGATE FUNCTIONS:  

● Calculate the sum of all salaries in the Finance department.  
● Find the minimum age among all employees.  

4. GROUP BY:  

● List the maximum salary for each location.  
● Calculate the average salary for each designation containing the word 'Analyst'.  

5. HAVING:  

●  Find departments with less than 3 employees.  
●  Find locations with female employees whose average age is below 30.  

Joins:  

1. INNER JOIN:  
● List employee names, their designations, and department names where 
employees are assigned to a department.  
2. LEFT JOIN:  
● List all departments along with the total number of employees in each 
department, including departments with no employees.  
3. RIGHT JOIN:  
● Display all locations along with the names of employees assigned to each location. 
If no employees are assigned to a location, display NULL for employee name. 
4. CROSS JOIN 
●  Show all possible combinations of departments and locations. 
5. SELF JOIN: 
● Show pairs of employees working in the same department, excluding self-pairs. 
Windows function 
● Write a window function query to rank employees by salary using rank(). 
● Write a window function query to rank employees by salary within each department 
using DENSE_RANK() 
● Write a window function query, Running total salary by department
