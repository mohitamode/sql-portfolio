<h2><a href="https://leetcode.com/problems/second-highest-salary">Second Highest Salary</a></h2> <img src="https://img.shields.io/badge/Difficulty-Medium-orange" alt="Difficulty: Medium" /><hr><p>Table: <code>Employee</code></p>

<pre>
+-------------+------+
| Column Name | Type |
+-------------+------+
| id          | int  |
| salary      | int  |
+-------------+------+
id is the primary key (column with unique values) for this table.
Each row of this table contains information about the salary of an employee.
</pre>

<p>&nbsp;</p>

<p>Write a solution to find&nbsp;the second highest salary from the <code>Employee</code> table. If there is no second highest salary,&nbsp;return&nbsp;<code>null (return&nbsp;None in Pandas)</code>.</p>

<p>The result format is in the following example.</p>

<p>&nbsp;</p>
<p><strong class="example">Example 1:</strong></p>

<pre>
<strong>Input:</strong> 
Employee table:
+----+--------+
| id | salary |
+----+--------+
| 1  | 100    |
| 2  | 200    |
| 3  | 300    |
+----+--------+
<strong>Output:</strong> 
+---------------------+
| SecondHighestSalary |
+---------------------+
| 200                 |
+---------------------+
</pre>

<p><strong class="example">Example 2:</strong></p>

<pre>
<strong>Input:</strong> 
Employee table:
+----+--------+
| id | salary |
+----+--------+
| 1  | 100    |
+----+--------+
<strong>Output:</strong> 
+---------------------+
| SecondHighestSalary |
+---------------------+
| null                |
+---------------------+
</pre>

<hr>

### Maintainer
**Mohit Shyam Amode**
Data Analyst
Email: mohitshyamamode@gmail.com
LinkedIn: linkedin.com/in/mohitamode

### About the Developer
Mohit is a Data Analyst with over 4 years of professional experience specializing in SQL, Python, and structured data analysis. His expertise includes query optimization, data visualization, and translating complex operational requirements into actionable insights. He maintains this repository as part of a collection of optimized SQL solutions and data analysis workflows.