# COVID-19 SQL exploration

A guided portfolio exercise exploring historical COVID-19 deaths and vaccination data with MySQL.

- [Read the case study](https://eugenetur.pages.dev/projects/covid-pipeline/)
- [Inspect the original SQL](./SQL%20Data%20Analysis%20Covid19Data.sql)
- [View the related Tableau dashboard](https://public.tableau.com/views/Covid19Project_16649621953250/Dashboard1)

## What to inspect

The script demonstrates joins on location/date, aggregate queries, a common table expression, rolling sums and a view for further visualisation. It is an annotated working document; the original source is retained.

The `SUM(new_vaccinations)` calculation counts vaccination doses. The original variable name `RollingPeopleVaccinated` must not be interpreted as a count of unique people. Execution-speed and row-volume benchmarks are not established by this repository.

## Opening the work

Use a MySQL environment supporting common table expressions and window functions. The script references `portfolioproject.covid19deaths` and `portfolioproject.covid22vac`. Raw source datasets and a reproducible import package are not included here; inspect the statements and adapt the database/table names before running them against your own copy of the data.

<details>
<summary>Original project notes</summary>

In this project, **I focused on optimizing MY SQL workflow and analyzing and visualizing COVID-19 data**. I used a variety of techniques to analyze the data, such as filtering and using aggregate functions. I also joined tables and created views for storing data for later visualization. I organized the data and did simple calculations with it. I also worked with temporary tables and used comments in my code. 
I also used a virtual table and organized my SQL code in a repository like GitHub.

**Here are some key points from the description of this project:**

1. Using data to find rough estimates of likelihood of dying from COVID-19
2. Analyzing and visualizing data
3. Techniques for analyzing and visualizing COVID-19 data using tools like Excel and Tableau.
4. Filtering data to make it more accurate
5. Using aggregate functions and grouping data by dates to correctly analyze the data
6. Joining two tables (COVID deaths and COVID vaccinations) on location and date to properly analyze the data
7. Creating views in SQL can be useful for storing data for later visualization
8. Organizing data in a specific order
9. Doing simple calculations with data from a database
10. Temporary table
11. Inserting data into a temporary table
12. Selecting data from a temporary table
13. Selecting data from a database
14. Using comments in code to track progress
15. Using specific comments in a portfolio project
16. Using a filter to look at data from specific countries
17. Joins, CTE's, Temp Tables, Windows Functions, Aggregate Functions, Creating Views, Converting Data Types

**Optimizing SQL Workflow:**

- It is important to consider how to handle errors, such as using the "DROP TABLE IF EXISTS" command to avoid issues when running queries multiple times
- GitHub can be used to store and share code, including SQL queries
- It is important to include comments and formatting in code to make it easy for others to understand and use.
- SQL can be used to manipulate and analyze data stored in a database
- It is good practice to include a "DROP TABLE IF EXISTS" statement at the beginning of a SQL query to prevent errors when running the query multiple times
- A view in SQL is a virtual table that can be created from the result of a SELECT statement, and can be used for later visualization
- It is a good idea to store and organize SQL code in a repository like GitHub for reference and to showcase portfolio projects to potential employers.


</details>
