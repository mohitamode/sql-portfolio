<h2><a href="https://leetcode.com/problems/product-price-at-a-given-date">Product Price at a Given Date</a></h2> <img src="https://img.shields.io/badge/Difficulty-Medium-orange" alt="Difficulty: Medium" /><hr><p>Table: <code>Products</code></p>

<pre>
+---------------+---------+
| Column Name   | Type    |
+---------------+---------+
| product_id    | int     |
| new_price     | int     |
| change_date   | date    |
+---------------+---------+
(product_id, change_date) is the primary key (combination of columns with unique values) of this table.
Each row of this table indicates that the price of some product was changed to a new price at some date.</pre>

<p> </p>

<p>Write a solution to find the prices of all products on <code>2019-08-16</code>. Assume the price of all products before any change is <code>10</code>.</p>

<p>Return the result table in <strong>any order</strong>.</p>

<p>The result format is in the following example.</p>

<p> </p>
<p><strong class="example">Example 1:</strong></p>

<pre>
<strong>Input:</strong> 
Products table:
+------------+-----------+-------------+
| product_id | new_price | change_date |
+------------+-----------+-------------+
| 1          | 20        | 2019-08-14  |
| 2          | 50        | 2019-08-14  |
| 1          | 30        | 2019-08-15  |
| 1          | 35        | 2019-08-16  |
| 2          | 65        | 2019-08-17  |
| 3          | 20        | 2019-08-18  |
+------------+-----------+-------------+
<strong>Output:</strong> 
+------------+-------+
| product_id | price |
+------------+-------+
| 2          | 50    |
| 1          | 35    |
| 3          | 10    |
+------------+-------+
</pre>

<hr>

## About the Developer

This project is maintained by Mohit Shyam Amode, a Data Analyst with over 4 years of professional experience in SQL, query optimization, and structured data analysis. With a background in translating operational requirements into actionable insights, Mohit focuses on building efficient data workflows and robust analytical solutions.

### Contact Information
- Name: Mohit Shyam Amode
- Role: Data Analyst
- Email: mohitshyamamode@gmail.com
- LinkedIn: linkedin.com/in/mohitamode
- Skills: SQL, Python, R, MongoDB, Tableau, Power BI, Query Optimization