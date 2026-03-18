<h2><a href="https://leetcode.com/problems/last-person-to-fit-in-the-bus">Last Person to Fit in the Bus</a></h2> <img src='https://img.shields.io/badge/Difficulty-Medium-orange' alt='Difficulty: Medium' /><hr><p>Table: <code>Queue</code></p>

<pre>
+-------------+---------+
| Column Name | Type    |
+-------------+---------+
| person_id   | int     |
| person_name | varchar |
| weight      | int     |
| turn        | int     |
+-------------+---------+
person_id column contains unique values.
This table has the information about all people waiting for a bus.
The person_id and turn columns will contain all numbers from 1 to n, where n is the number of rows in the table.
turn determines the order of which the people will board the bus, where turn=1 denotes the first person to board and turn=n denotes the last person to board.
weight is the weight of the person in kilograms.
</pre>

<p>&nbsp;</p>

<p>There is a queue of people waiting to board a bus. However, the bus has a weight limit of <code>1000</code><strong> kilograms</strong>, so there may be some people who cannot board.</p>

<p>Write a solution to find the <code>person_name</code> of the <strong>last person</strong> that can fit on the bus without