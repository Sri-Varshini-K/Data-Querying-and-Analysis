# Data Querying and Analysis

## Project Overview

This project focuses on querying and analyzing employee database records using MySQL. Building on the previous assignment involving database creation and constraints, this project applies SQL queries to retrieve, filter, sort, group, and analyze employee data across departments and locations.

## Objectives

- Retrieve unique values using `DISTINCT`.
- Rename output columns using `AS` aliases.
- Filter records using `WHERE` and comparison operators.
- Sort and limit results using `ORDER BY` and `LIMIT`.
- Perform calculations using aggregate functions.
- Group and filter aggregated data using `GROUP BY` and `HAVING`.
- Retrieve related information using `INNER JOIN`, `LEFT JOIN`, and `RIGHT JOIN`.

## Technologies Used

- **Database:** MySQL
- **Language:** SQL
- **Concepts:** Data Querying, Filtering, Sorting, Aggregation, Grouping, Joins

## Tasks Performed

### 1. Data Retrieval and Filtering
- Retrieve distinct employee salaries.
- Display employee age and salary with custom aliases.
- Find employees earning more than ₹50,000 who were hired before January 1, 2016.
- Update missing employee designations to `Data Scientist`.

### 2. Sorting and Limiting
- Sort employees by department ID in ascending order and salary in descending order.
- Retrieve the first five employees hired in 2018.

### 3. Aggregate Functions
- Calculate the total salary of employees in the Finance department.
- Find the minimum employee age.
- Determine the maximum salary for each location.
- Calculate average salaries for designations containing the word `Analyst`.

### 4. Grouping and Conditional Filtering
- Identify departments with fewer than three employees.
- Find locations where female employees have an average age below 30.

### 5. SQL Joins
- **INNER JOIN:** Retrieve employee names, designations, and department names for employees assigned to a department.
- **LEFT JOIN:** List all departments with employee counts, including departments without employees.
- **RIGHT JOIN:** Display all locations and their assigned employees, including locations without employees.

## Key Learnings

- Writing efficient SQL queries to retrieve relevant information.
- Applying filtering and sorting conditions.
- Using aggregate functions to summarize employee data.
- Grouping records to identify patterns and trends.
- Combining related tables using different join operations.
- Understanding how SQL supports data analysis and reporting.

## Conclusion

This assignment strengthened my practical SQL querying skills through employee data analysis, aggregation, conditional filtering, and table joins. It provided hands-on experience in extracting meaningful insights from relational databases.
