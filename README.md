# Employee Database - SQL Challenge

## Background
Welcome to the Employee Database project! In this assignment, you will work on data modeling, data engineering, and data analysis using six CSV files containing information about Pewlett Hackard's employees from the 1980s and 1990s.

## Before You Begin
1. Create a new repository for this project called `sql-challenge`. Do not add this homework assignment to an existing repository.
2. Clone the new repository to your computer.
3. Inside your local Git repository, create a directory for the SQL challenge, like `EmployeeSQL`.
4. Add your files to this folder.
5. Push these changes to GitHub.

## Instructions
This assignment is divided into three parts: data modeling, data engineering, and data analysis.

### Data Modeling
- Inspect the CSVs and sketch out an ERD using a tool like [Quick Database Diagrams](http://www.quickdatabasediagrams.com).

### Data Engineering
- Create a table schema for each of the six CSV files, specifying data types, primary keys, foreign keys, and other constraints.
- Import each CSV file into the corresponding SQL table.

### Data Analysis
Once you have a complete database, perform the following steps:

1. List the details of each employee: employee number, last name, first name, sex, and salary.
2. List first name, last name, and hire date for employees hired in 1986.
3. List the manager of each department with department number, department name, manager's employee number, last name, and first name.
4. List the department of each employee with employee number, last name, first name, and department name.
5. List first name, last name, and sex for employees with first name "Hercules" and last names beginning with "B."
6. List all employees in the Sales department with employee number, last name, first name, and department name.
7. List all employees in the Sales and Development departments with employee number, last name, first name, and department name.
8. List the frequency count of employee last names in descending order.

### Bonus (Optional)
- Import the SQL database into Pandas and create visualizations:
    - Create a histogram to visualize the most common salary ranges for employees.
    - Create a bar chart of average salary by title.

## Submission
1. Create an image file of your ERD.
2. Create a .sql file of your table schemata.
3. Create a .sql file of your queries.
4. (Optional) Create a Jupyter notebook for the bonus analysis.
5. Create and upload a repository with the above files to GitHub and post a link on BootCamp Spot.
