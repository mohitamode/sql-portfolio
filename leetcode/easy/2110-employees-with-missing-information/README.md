<h2><a href="https://leetcode.com/problems/employees-with-missing-information">Employees With Missing Information</a></h2> <img src="https://img.shields.io/badge/Difficulty-Easy-brightgreen" alt="Difficulty: Easy" /><hr><p>Table: <code>Employees</code></p>

<pre>
+-------------+---------+
| Column Name | Type    |
+-------------+---------+
| employee_id | int     |
| name        | varchar |
+-------------+---------+
employee_id is the column with unique values for this table.
Each row of this table indicates the name of the employee whose ID is employee_id.
</pre>

<p>&nbsp;</p>

<p>Table: <code>Salaries</code></p>

<pre>
+-------------+---------+
| Column Name | Type    |
+-------------+---------+
| employee_id | int     |
| salary      | int     |
+-------------+---------+
employee_id is the column with unique values for this table.
Each row of this table indicates the salary of the employee whose ID is employee_id.
</pre>

<p>&nbsp;</p>

<p>Write a solution to report the IDs of all the employees with <strong>missing information</strong>. The information of an employee is missing if:</p>

<ul>
	<li>The employee's <strong>name</strong> is missing, or</li>
	<li>The employee's <strong>salary</strong> is missing.</li>
</ul>

<p>Return the result table ordered by <code>employee_id</code> <strong>in ascending order</strong>.</p>

<p>The result format is in the following example.</p>

<p>&nbsp;</p>
<p><strong class="example">Example 1:</strong></p>

<pre>
<strong>Input:</strong> 
Employees table:
+-------------+----------+
| employee_id | name     |
+-------------+----------+
| 2           | Crew     |
| 4           | Haven    |
| 5           | Kristian |
+-------------+----------+
Salaries table:
+-------------+--------+
| employee_id | salary |
+-------------+--------+
| 5           | 76071  |
| 1           | 22517  |
| 4           | 63539  |
+-------------+--------+
<strong>Output:</strong> 
+-------------+
| employee_id |
+-------------+
| 1           |
| 2           |
+-------------+
<strong>Explanation:</strong> 
Employees 1, 2, 4, and 5 are working at this company.
The name of employee 1 is missing.
The salary of employee 2 is missing.
</pre>

<hr>

<h3>Maintainer</h3>

<p>This repository is maintained by Mohit Shyam Amode. For any questions regarding the implementation or data analysis workflows, please reach out through the contact details below.</p>

<p>
- Email: mohitshyamamode@gmail.com<br>
- LinkedIn: linkedin.com/in/mohitamode
</p>

<h3>About the Developer</h3>

<p>Mohit Shyam Amode is a Data Analyst with over 4 years of professional experience in SQL, Python, and structured data analysis. He specializes in query optimization, data visualization, and translating complex operational requirements into actionable insights. His technical expertise includes working with MongoDB, Tableau, Power BI, and various programming languages to build efficient reporting workflows.</p>