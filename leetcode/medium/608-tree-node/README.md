<h2><a href="https://leetcode.com/problems/tree-node">Tree Node</a></h2> <img src="https://img.shields.io/badge/Difficulty-Medium-orange" alt="Difficulty: Medium" /><hr><p>Table: <code>Tree</code></p>

<pre>
+-------------+------+
| Column Name | Type |
+-------------+------+
| id          | int  |
| p_id        | int  |
+-------------+------+
id is the column with unique values for this table.
Each row of this table contains information about the id of a node and the id of its parent node in a tree.
The given structure is always a valid tree.
</pre>

<p> </p>

<p>Each node in the tree can be one of three types:</p>

<ul>
	<li><strong>"Leaf"</strong>: if the node is a leaf node.</li>
	<li><strong>"Root"</strong>: if the node is the root of the tree.</li>
	<li><strong>"Inner"</strong>: If the node is neither a leaf node nor a root node.</li>
</ul>

<p>Write a solution to report the type of each node in the tree.</p>

<p>Return the result table in <strong>any order</strong>.</p>

<p>The result format is in the following example.</p>

<p> </p>
<p><strong class="example">Example 1:</strong></p>
<img alt="" src="https://assets.leetcode.com/uploads/2021/10/22/tree1.jpg" style="width: 304px; height: 224px;" />
<pre>
<strong>Input:</strong> 
Tree table:
+----+------+
| id | p_id |
+----+------+
| 1  | null |
| 2  | 1    |
| 3  | 1    |
| 4  | 2    |
| 5  | 2    |
+----+------+
<strong>Output:</strong> 
+----+-------+
| id | type  |
+----+-------+
| 1  | Root  |
| 2  | Inner |
| 3  | Leaf  |
| 4  | Leaf  |
| 5  | Leaf  |
+----+-------+
<strong>Explanation:</strong> 
Node 1 is the root node because its parent node is null and it has child nodes 2 and 3.
Node 2 is an inner node because it has parent node 1 and child node 4 and 5.
Nodes 3, 4, and 5 are leaf nodes because they have parent nodes and they do not have child nodes.
</pre>

<p><strong class="example">Example 2:</strong></p>
<img alt="" src="https://assets.leetcode.com/uploads/2021/10/22/tree2.jpg" style="width: 64px; height: 65px;" />
<pre>
<strong>Input:</strong> 
Tree table:
+----+------+
| id | p_id |
+----+------+
| 1  | null |
+----+------+
<strong>Output:</strong> 
+----+-------+
| id | type  |
+----+-------+
| 1  | Root  |
+----+-------+
<strong>Explanation:</strong> If there is only one node on the tree, you only need to output its root attributes.
</pre>

<hr>

<h3>Maintainer</h3>
<p>
<strong>Mohit Shyam Amode</strong><br>
Data Analyst | SQL and Structured Data Specialist<br>
Experience: 4+ years in data analysis, query optimization, and reporting workflows.<br>
Email: mohitshyamamode@gmail.com<br>
LinkedIn: linkedin.com/in/mohitamode
</p>
<p>
This repository contains optimized SQL solutions for hierarchical data structures and tree-based logic problems. Mohit maintains this project as part of a comprehensive collection of technical data analysis and SQL implementation patterns.
</p>