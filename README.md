# ScienceQtech-Employee-Performance-Mapping

ScienceQtech is a startup that works in the Data Science field. They have worked on fraud detection, market basket, self-driving cars, supply chain, algorithmic early detection of lung cancer, customer sentiment, and the drug discovery field. With the annual appraisal cycle around the corner and to finalise the employee performance mapping, the HR department has asked me, as a junior database administrator, to generate reports on employee details, their performance, project(s) they have undertaken, and to analyse the employee database including to extract specific data based on different requirements. These include, to find the maximum salary of the employees, calculating bonuses, to find the extra cost of the expenses, and to inquire on whether all jobs meet the organization's profile standard.

Specific tasks completed:
1. Created a database named employee, then imported the data_science_team.csv, proj_table.csv and emp_record_table.csv data tables into the employee database.
2. Created an ER diagram for the employee database.
3. Wrote a query to fetch EMP_ID, FIRST_NAME, LAST_NAME, GENDER, and DEPARTMENT from the employee record table, and making a list of employees and details of their department.
4. Wrote a query to fetch EMP_ID, FIRST_NAME, LAST_NAME, GENDER, DEPARTMENT, and EMP_RATING if the EMP_RATING is: 
o	less than two
o	greater than four 
o	between two and four
5. Wrote a query to concatenate the FIRST_NAME and the LAST_NAME of employees in the Finance department from the employee table and then give the resultant column alias as NAME.
6. Wrote a query to list only those employees who have someone reporting to them. Also, showing the number of reporters (including the President).
7. Wrote a query to list down all the employees from the healthcare and finance departments using union. Using data from the employee record table.
8. Wrote a query to list down employee details such as EMP_ID, FIRST_NAME, LAST_NAME, ROLE, DEPARTMENT, and EMP_RATING grouped by dept. Also included the respective employee rating along with the max emp rating for the department.
9. Wrote a query to calculate the minimum and the maximum salary of the employees in each role. Took data from the employee record table.
10. Wrote a query to assign ranks to each employee based on their experience. Took data from the employee record table.
11. Wrote a query to create a view that displays employees in various countries whose salary is more than six thousand. Took data from the employee record table.
12. Wrote a nested query to find employees with experience of more than ten years. Took data from the employee record table.
13. Wrote a query to create a stored procedure to retrieve the details of the employees whose experience is more than three years. Took data from the employee record table.
14. Wrote a query using stored functions in the project table to check whether the job profile assigned to each employee in the data science team matches the organization’s set standard.
Criteria are:
o	For an employee with experience less than or equal to 2 years assigned 'JUNIOR DATA SCIENTIST',
o	For an employee with the experience of 2 to 5 years assigned 'ASSOCIATE DATA SCIENTIST',
o	For an employee with the experience of 5 to 10 years assigned 'SENIOR DATA SCIENTIST',
o	For an employee with the experience of 10 to 12 years assigned 'LEAD DATA SCIENTIST',
o	For an employee with the experience of 12 to 16 years assigned 'MANAGER'.
15. Created an index to improve the cost and performance of the query to find the employee whose FIRST_NAME is ‘Eric’ in the employee table after checking the execution plan.
16. Wrote a query to calculate the bonus for all the employees, based on their ratings and salaries (Use the formula: 5% of salary * employee rating).
17. Wrote a query to calculate the average salary distribution based on the continent and country. Take data from the employee record table.
