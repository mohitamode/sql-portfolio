<h2><a href="https://leetcode.com/problems/replace-employee-id-with-the-unique-identifier">Replace Employee ID With The Unique Identifier</a></h2> <img src='https://img.shields.io/badge/Difficulty-Easy-brightgreen' alt='Difficulty: Easy' /><hr><p>Table: <code>Employees</code></p>

<pre>
+---------------+---------+
| Column Name   | Type    |
+---------------+---------+
| id            | int     |
| name          | varchar |
+---------------+---------+
id is the primary key (column with unique values) for this table.
Each row of this table contains the id and the name of an employee in a company.
</pre>

<p> </p>

<p>Table: <code>EmployeeUNI</code></p>

<pre>
+---------------+---------+
| Column Name   | Type    |
+---------------+---------+
| id            | int     |
| unique_id     | int     |
+---------------+---------+
(id, unique_id) is the primary key (combination of columns with unique values) for this table.
Each row of this table contains the id and the corresponding unique id of an employee in the company.
</pre>

<p> </p>

<p>Write a solution to show the <strong>unique ID </strong>of each user, If a user does not have a unique ID replace just show <code>null</code>.</p>

<p>Return the result table in <strong>any</strong> order.</p>

<p>The result format is in the following example.</p>

<p> </p>
<p><strong class="example">Example 1:</strong></p>

<pre>
<strong>Input:</strong> 
Employees table:
+----+----------+
| id | name     |
+----+----------+
| 1  | Alice    |
| 7  | Bob      |
| 11 | Meir     |
| 90 | Winston  |
| 3  | Jonathan |
+----+----------+
EmployeeUNI table:
+----+-----------+
| id | unique_id |
+----+-----------+
| 3  | 1         |
| 11 | 2         |
| 90 | 3         |
+----+-----------+
<strong>Output:</strong> 
+-----------+----------+
| unique_id | name     |
+-----------+----------+
| null      | Alice    |
| null      | Bob      |
| 2         | Meir     |
| 3         | Winston  |
| 1         | Jonathan |
+-----------+----------+
<strong>Explanation:</strong> 
Alice and Bob do not have a unique ID, We will show null instead.
The unique ID of Meir is 2.
The unique ID of Winston is 3.
The unique ID of Jonathan is 1.
</pre>

<hr>

<h3>Maintainer</h3>
<p><strong>Mohit Shyam Amode</strong><br>
Data Analyst<br>
Email: mohitshyamamode@gmail.com<br>
LinkedIn: linkedin.com/in/mohitamode</p>

<p>Professional Data Analyst with over 4 years of experience in SQL, query optimization, and structured data analysis. This project is part of a collection of technical solutions focused on efficient data transformation and reporting workflows. I actively maintain this repository to ensure high-quality documentation of SQL logic and data handling techniques.</p>