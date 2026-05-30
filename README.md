# SQL Data Analytics Project

## Introduction

Welcome to my SQL Data Analytics Project. In this project, I explored the data analyst job market using SQL and PostgreSQL to identify top-paying jobs, in-demand skills, and the relationship between salary and skill demand.

📁 SQL Queries: [ProjectSQL](./ProjectSQL)



## Background

I created this project to better understand the data analyst job market and identify which skills employers value most. My goal was to use real-world job posting data to answer practical career questions and strengthen my SQL skills through hands-on analysis.

The dataset used in this project comes from Luke Barousse's SQL Data Analytics course and includes information on job titles, salaries, locations, and required skills.

### Key Questions

1. What are the highest-paying data analyst jobs?
2. What skills are required for those jobs?
3. What skills are most in demand for data analysts?
4. Which skills are associated with higher salaries?
5. What are the most valuable skills based on both demand and salary?



## Tools Used

- **SQL** – Used to query, filter, join, and analyze data.
- **PostgreSQL** – Database management system used to store and manage the dataset.
- **Visual Studio Code (VS Code)** – Used to write and execute SQL queries.
- **Git & GitHub** – Used for version control and project documentation.



## Analysis

### 1. Top-Paying Data Analyst Jobs

This analysis identified the highest-paying data analyst positions by filtering for data analyst roles with reported salaries and ranking them by annual compensation.

### 2. Skills Required for Top-Paying Jobs

By joining job posting data with skill requirements, I identified which technical skills are most commonly associated with the highest-paying analyst positions.

### 3. Most In-Demand Skills

This analysis measured skill demand by counting how frequently specific skills appeared across data analyst job postings. 

Key Finding: SQL was by far the most requested skill, appearing in over 7,000 job postings. Employers consistently seek a combination of SQL, Python, and data visualization skills.

| Skill    | Demand Count |
| -------- | -----: |
| SQL      |  7,291 |
| Excel    |  4,611 |
| Python   |  4,330 |
| Tableau  |  3,745 |
| Power BI |  2,609 |


### 4. Highest-Paying Skills

I calculated the average salary associated with individual skills to determine which technical skills command the highest compensation.

Key Finding: While PySpark had the highest average salary, it appeared in far fewer job postings than SQL. This suggests that high salary does not necessarily indicate broad market demand.

| Skill     | Avg Salary |
| --------- | ---------: |
| PySpark   |      $208K |
| Bitbucket |      $189K |
| Couchbase |      $161K |
| Watson    |      $161K |
| DataRobot |      $155K |


### 5. Most Optimal Skills

This analysis combined salary and demand data to identify skills that offer the strongest balance between market demand and earning potential. 

Key Finding: Python and Tableau emerged as strong "optimal skills" because they combine substantial demand with competitive salaries. Cloud technologies such as Snowflake and Azure offer higher salaries but appear in fewer postings.
| Skill     | Demand | Avg Salary |
| --------- | -----: | ---------: |
| Python    |    236 |      $101K |
| Tableau   |    230 |       $99K |
| R         |    148 |      $100K |
| Looker    |     49 |      $104K |
| Snowflake |     37 |      $113K |




## What I Learned

Throughout this project, I strengthened several important SQL and data analysis skills:

- Writing complex SQL queries using joins, CTEs, and aggregate functions.
- Using `GROUP BY`, `COUNT()`, and `AVG()` to summarize large datasets.
- Transforming business questions into data-driven analyses.
- Working with relational databases and structured datasets.
- Presenting analytical findings in a clear and organized format.



## Key Insights

- High-paying data analyst positions can offer salaries well above industry averages.
- SQL consistently appeared as one of the most valuable skills across nearly every analysis.
- Technical skills such as Python, Tableau, Power BI, and cloud-related technologies continue to be highly sought after.
- Specialized technical skills often command significantly higher salaries.
- The strongest long-term career opportunities tend to come from skills that are both highly demanded and highly compensated.



## Conclusion

## Conclusion

This project helped me develop stronger SQL skills by working through real-world business questions and analyzing a large job posting dataset. Beyond learning more advanced SQL concepts such as joins, CTEs, aggregations, and filtering, it also strengthened my data analysis and critical thinking skills by forcing me to interpret results rather than simply generate them.

One of the most interesting takeaways was recognizing that the highest-paying skills are not always the most valuable skills. While specialized technologies such as PySpark and Snowflake were associated with higher salaries, SQL consistently appeared as the most in-demand skill across the job market. This highlighted the importance of looking beyond a single metric and considering both demand and salary when evaluating career opportunities.

Overall, this project provided valuable insight into the data analyst job market while giving me hands-on experience using SQL to transform raw data into meaningful business insights.

