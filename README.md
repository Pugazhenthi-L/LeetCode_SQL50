<div align="center">
    <img src="SQL_logo.png" alt="Logo" width="80" height="80">
    <h1 align="center">LeetCode_SQL50</h1>
</div>
<details>
<summary>Table of Content</summary>
<ol>
    <li>
        <a href="#select">Select</a>
    </li>
    <li>
        <a href="#basic-joins">Basic of Joins</a>
    </li>
</ol>

</details>

## Select 

Q-1) https://leetcode.com/problems/recyclable-and-low-fat-products/?envType=study-plan-v2&envId=top-sql-50 

    select product_id from Products where low_fats = 'Y' and recyclable = 'Y';

Q-2) https://leetcode.com/problems/find-customer-referee/?envType=study-plan-v2&envId=top-sql-50

    select name from Customer where referee_id != 2 or referee_id is null;

Q-3) https://leetcode.com/problems/big-countries/?envType=study-plan-v2&envId=top-sql-50

    select name,population,area from world where area >= 3000000 or population >= 25000000;

Q-4) https://leetcode.com/problems/article-views-i/?envType=study-plan-v2&envId=top-sql-50

    select distinct author_id as id from Views where author_id = viewer_id order by author_id;

Q-5) https://leetcode.com/problems/invalid-tweets/?envType=study-plan-v2&envId=top-sql-50

    select tweet_id from Tweets where length(content)>15;

## Basic Joins

Q-6) 
