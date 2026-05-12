Project Overview

This project contains 65 SQL queries for practicing and understanding SQL concepts using an Employee Management Database.

The queries cover:

Basic SELECT statements
WHERE conditions
Pattern matching using LIKE
Date functions
Aggregate functions
GROUP BY and HAVING
Sorting with ORDER BY
Joins
Subqueries
Nested queries
Advanced SQL practice questions
Database Schema
Employee Table
Column Name	Data Type	Description
emp_id	INT	Employee ID
name	VARCHAR	Employee Name
age	INT	Employee Age
salary	DECIMAL	Employee Salary
hire_date	DATE	Hiring Date
department_id	INT	Department Reference
Department Table
Column Name	Data Type	Description
department_id	INT	Department ID
name	VARCHAR	Department Name
Project Table
Column Name	Data Type	Description
project_id	INT	Project ID
name	VARCHAR	Project Name
department_id	INT	Department Reference
SQL Concepts Covered
1. Basic Queries

Examples:

Select all employees
Select specific columns
Filter records using conditions

Queries:

1 to 5
2. Pattern Matching

Using LIKE operator.

Examples:

Names starting with a letter
Names ending with a letter
Character position matching

Queries:

6 to 10
3. Date Functions

Working with dates and time filtering.

Examples:

Employees hired in a specific year
Employees hired before a date
Employees hired in last 2 years

Queries:

11 to 15
4. Aggregate Functions

Using:

SUM()
AVG()
MIN()
MAX()
COUNT()

Queries:

16 to 24
5. GROUP BY and HAVING

Grouping records and filtering grouped data.

Examples:

Average salary per department
Departments with more than 2 employees
Departments with high salary averages

Queries:

25 to 30
6. Sorting Data

Using ORDER BY.

Examples:

Sort by salary
Sort by age
Multiple column sorting

Queries:

31 to 35
7. JOIN Operations

Using:

INNER JOIN
LEFT JOIN

Examples:

Employee with department names
Projects with departments
Departments without employees

Queries:

36 to 43
8. Subqueries and Nested Queries

Advanced SQL concepts using nested queries.

Examples:

Highest salary employee
Salary above department average
Second and third highest salary
Same department as another employee

Queries:

44 to 65
Features
Beginner to Advanced SQL Practice
Real-world Employee Management examples
Covers interview-level SQL problems
Useful for:
College labs
Placement preparation
Database Management Systems (DBMS)
SQL interview practice
Technologies Used
SQL
MySQL
How to Run
Create the database.
Create the tables:
Employee
Department
Project
Insert sample data.
Run the SQL queries one by one.
