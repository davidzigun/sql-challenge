# sql-challenge

What was accomplished in this assignment:

1. After reviewing the data in the CSV files, QuickDBD (a object mapping site for tables to be added to a database) was utilized to create an Entity Relation Diagram (ERD) to map the connections between the various sets of data necessary for a cohesive database. Six CSV files were used, their data types defined, as well as the primary keys (unique identifiers local to that particular table of data) and foreign keys (unique identifiers from an external table, required to define relationships).

The diagram of the resulting connections can be seen below.
EmployeeSQL/QuickDBD-SQLChallenge IMG.png

After importing the files to populate the created tables, SQL queries were created to identify the information requested in the Data Analysis items (seen below). The SQL query can be seen in the "SQLChallenge Query File" found in the "EmployeeSQL" folder.

Data Analysis
List the following details of each employee: employee number, last name, first name, sex, and salary
List first name, last name, and hire date for employees who were hired in 1986
List the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name
List the department of each employee with the following information: employee number, last name, first name, and department name
List first name, last name, and sex for employees whose first name is "Hercules" and last names begin with "B"
List all employees in the Sales department, including their employee number, last name, first name, and department name
List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name
In descending order, list the frequency count of employee last names, i.e., how many employees share each last name
