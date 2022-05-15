# Pewlett-Hackard-Analysis

Employee database analysis on retiring employees using SQL and pgAdmin
## Overview
The goal of this project is to determine who will be retiring in the next few years and how many of them will be eligible for the mentorship program. We will be generating these lisst to help prepare Bobby's manager for the "Silver Tsunami" in which roughly tens of thousands of employees will be elibible for retirment. 

## Resources
- Orginal datasets:
    - departments.csv
    - dept_emp.csv
    - dept_manager.csv
    - employees.csv
    - salaries.csv
    - titles.csv

- Software:
    - SQL
    - PostgreSQL
    - pgAdmin

## Questions to be Answered
1. How many roles will need to be filled as the "silver tsunami" begins to make an impact?
2. Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?

# Summary

As the Silver Tsunami begins to make an impact, the company will be looking at a potential employee loss due to retirement of 72 thousand employees.  Please see the below chart for the breakdown titles that will need to be replaced.

![Retiring Titles](/Data/retiring_titles.png)


Unfortunatly there are only 1549 employees who will be eligible for the mentorship program.  There will not be enough retirement-ready employees to mentor the next generation of Pewlett Hackard employees.  Per the below chart, looks like Senior staff will be the hardest hit with 25916 retiring with only 441 eligible for the mentorship program.

![Mentorship Titles](/Data/mentorship_titles.png)