# SQL-Employee-Salaries

# Challenge:
- Write a query that prints a list of employee names (i.e.: the name attribute) for employees in Employee having a salary greater than $2000 per month who have been employees for less than 10 months. Sort your result by ascending employee_id.

- The Employee table containing employee data for a company is described as follows:

![evdbufcb 2jk](https://github.com/MarcvWaes/SQL-Employee-Names/assets/120553175/707d5dae-4ef9-4464-a9b5-12ad7db08cde)

- Where employee_id is an employee's ID number, name is their name, months is the total number of months they've been working for the company, and salary is their monthly salary.

- Sample input:

![ck1ucpkm ir0](https://github.com/MarcvWaes/SQL-Employee-Names/assets/120553175/fb6aa5f5-f941-457c-b830-baac4071d619)

# Solution:
- SELECT NAME
- FROM EMPLOYEE
- WHERE SALARY > 2000 AND MONTHS < 10
- ORDER BY EMPLOYEE_ID ASC;

# Output:
- Rose 
- Patrick 
- Lisa 
- Amy 
- Pamela 
- Jennifer 
- Julia 
- Kevin 
- Paul 
- Donna
- .....
