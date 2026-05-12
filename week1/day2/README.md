This project contains basic and intermediate SQL queries using an Employees table.
The queries are categorized based on SQL concepts such as:

SELECT
WHERE
GROUP BY
HAVING
ORDER BY / TOP
DISTINCT
Comparison Operators
Logical Operators
IN / NOT IN
BETWEEN
LIKE

These queries are useful for:

SQL beginners
Database practice
College assignments
Interview preparation
Table Used
Employees Table Structure
Column Name	Data Type	Description
emp_id	INT	Employee ID
emp_name	VARCHAR	Employee Name
department	VARCHAR	Department Name
salary	INT	Employee Salary
city	VARCHAR	Employee City
experience	INT	Years of Experience
Query Categories
1. SELECT Queries

Basic data retrieval queries.

Examples:

Display all employee details
Display employee names and salaries
Display employees from IT department

Concepts Used:

SELECT
FROM
2. WHERE Queries

Filter records based on conditions.

Examples:

Salary greater than 70000
Employees from Hyderabad
Experience less than 4 years

Concepts Used:

WHERE
Conditional filtering
3. GROUP BY Queries

Group records and apply aggregate functions.

Examples:

Total salary department-wise
Average salary in each department
Employee count city-wise

Concepts Used:

GROUP BY
SUM()
AVG()
COUNT()
MAX()
MIN()
4. HAVING Queries

Filter grouped records after aggregation.

Examples:

Departments with more than 3 employees
Departments with average salary > 60000

Concepts Used:

HAVING
Aggregate filtering
5. TOP / LIMIT Queries

Retrieve top records.

Examples:

Top 5 highest paid employees
Highest experienced employees

Concepts Used:

ORDER BY
LIMIT
6. DISTINCT Queries

Retrieve unique values.

Examples:

Distinct department names
Distinct city names

Concept Used:

DISTINCT
7. Comparison Operator Queries

Compare values using operators.

Operators Used:

>
<
>=
<=
<>

Examples:

Salary >= 80000
Experience <= 3
8. Logical Operator Queries

Combine conditions.

Operators Used:

AND
OR
NOT

Examples:

IT employees with salary > 70000
Employees from Hyderabad OR Bangalore
9. IN and NOT IN Queries

Check multiple values easily.

Examples:

Employees from Hyderabad or Mumbai
Departments not in HR and Sales

Concepts Used:

IN
NOT IN
10. BETWEEN Queries

Filter values within a range.

Examples:

Salary between 50000 and 80000
Experience between 3 and 6

Concept Used:

BETWEEN
11. LIKE Operator Queries

Pattern matching in text.

Examples:

Names starting with 'R'
Names ending with 'a'
Names containing 'v'

Concept Used:

LIKE

Wildcards:

% → Multiple characters
_ → Single character
SQL Concepts Covered
Data Retrieval
Filtering
Sorting
Aggregation
Grouping
Pattern Matching
Conditional Operators
Logical Operations
Database Compatibility


LIMIT works in MySQL/PostgreSQL/SQLite
SQL Server uses TOP
Oracle uses ROWNUM or FETCH FIRST
