# Employee Database with SQL

## Overview of Project

1. Create a table that contains the number of retiring employees by title.
2. Create a table that contains the employees eligible for the mentorship program.

## Results

The analysis of the employee data shows that:

- Some employees have multiple titles in the database due to promotions or changing positions. I used the "DISTINCT ON" statement to create a table that contains the current title of each retirement-age employee.

<img width="512" alt="unique_titles" src="https://user-images.githubusercontent.com/100643519/164933195-7921e2d3-c89c-451a-a57d-48a256973f6d.png">

- There are currently 72,458 retirement-age employees.
- Of the 72,458 retirement-age employees, 50,842 are Senior Engineers and Senior Staff.

<img width="213" alt="retiring_titles" src="https://user-images.githubusercontent.com/100643519/164933290-fc70c7b6-451e-47b1-b47b-63896c8e0c43.png">

- There are 1,549 current employees that are eligible for the mentorship program.

<img width="727" alt="mentorship_eligibility" src="https://user-images.githubusercontent.com/100643519/164933513-f29aee80-c168-4053-add3-cf5ed3106eab.png">

## Summary

- The results of my analysis show that Pewlett Hackard will need to fill up to 72,458 roles as the retirement-age employees begin to exit the workforce.
- Approximately 2% of the current, retirement-age employees are eligible for the mentorship program.
- In the Retirement Titles table, I would add the hire date column from the Employee table and add a filter with a range of hire dates to provide more insight into the number of employees who are eligible for retirement.
- I would create an additional table similar to the Mentorship Eligibility table to find the number of current employees who are eligible mentees. I would reuse the Mentorship Eligibility query and edit the birthdate range. I would also add a filter to the from_date column to include employees with a specified tenure. Then you could determine the number of eligible mentors by title and the number of eligible mentees by title. This data would provide insight into whether there are enough mentors to help develop the next generation of Pewlett Hackard employees.
