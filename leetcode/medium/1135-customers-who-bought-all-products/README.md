<h2><a href="https://leetcode.com/problems/customers-who-bought-all-products">Customers Who Bought All Products</a></h2> <img src="https://img.shields.io/badge/Difficulty-Medium-orange" alt="Difficulty: Medium" /><hr><p>Table: <code>Customer</code></p>

<pre>
+-------------+---------+
| Column Name | Type    |
+-------------+---------+
| customer_id | int     |
| product_key | int     |
+-------------+---------+
This table may contain duplicates rows. 
<code>customer_id</code> is not NULL.
product_key is a foreign key (reference column) to <code>Product</code> table.
</pre>

<p> </p>

<p>Table: <code>Product</code></p>

<pre>
+-------------+---------+
| Column Name | Type    |
+-------------+---------+
| product_key | int     |
+-------------+---------+
product_key is the primary key (column with unique values) for this table.
</pre>

<p> </p>

<p>Write a solution to report the customer ids from the <code>Customer</code> table that bought all the products in the <code>Product</code> table.</p>

<p>Return the result table in <strong>any order</strong>.</p>

<p>The result format is in the following example.</p>

<p> </p>
<p><strong class="example">Example 1:</strong></p>

<pre>
<strong>Input:</strong> 
Customer table:
+-------------+-------------+
| customer_id | product_key |
+-------------+-------------+
| 1           | 5           |
| 2           | 6           |
| 3           | 5           |
| 3           | 6           |
| 1           | 6           |
+-------------+-------------+
Product table:
+-------------+
| product_key |
+-------------+
| 5           |
| 6           |
+-------------+
<strong>Output:</strong> 
+-------------+
| customer_id |
+-------------+
| 1           |
| 3           |
+-------------+
<strong>Explanation:</strong> 
The customers who bought all the products (5 and 6) are customers with IDs 1 and 3.
</pre>

<hr>

## Maintainer
**Mohit Shyam Amode**
Data Analyst
Email: mohitshyamamode@gmail.com
LinkedIn: linkedin.com/in/mohitamode

### About the Developer
I am a Data Analyst with over 4 years of professional experience specializing in SQL, query optimization, and structured data analysis. My expertise includes dashboard development, reporting workflows, and translating operational requirements into actionable insights. I actively maintain this repository as part of a collection of optimized SQL solutions and data analysis patterns.

**Key Skills:** Python, SQL, R, JavaScript, C, C++, R Shiny, Streamlit, LangChain