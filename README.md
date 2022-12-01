# Assignment 2 - Database Design Process from start to finish using MySQL Workbench
This assignment will meet the following objectives:

**Course Objectives:**
1. Organize data in ways to emphasize relationships 

2. Perform CRUD operations from both relational and NoSQL databases 

**Weekly Objectives:**

1.  Create advanced SQL queries that make use of the JOIN and HAVE clause
 

## Instructions
For this assignment, you will decide on a problem domain and create a database of your choosing.  This assignment will require you to document business rules and generate a database from the business rules




## Requirements
### Deliverable 1 - Introducing Problem Domain and Business Rules ( 15 Points)
For this deliverable, you will propose a problem domain and generate business rules that address the problem domain. The business rules you identify will consist of relationships, constraints, and data you will need to collect. Within the readme file for this repository, you will identify each of the entities along with a brief description describing the purpose of the entity and the data the entity will collect, You will also need to identify the relationships between entities and any assumptions or questions you have for the client after reading the business description. You will ultimately decide the answer on behalf of the problem domain when you list your assumptions.

Once you complete the documentation of business rules within the README.md file, you will use the business rules to create an ER Diagram within MySQL Workbench.  When creating the problem domain and ER Diagram, make sure your database contains a **minimum of 4 tables but no more than 8** with at least **one table serving as an associative entity**.  When completing this deliverable, make sure to adhere to the following items below.
1. Make sure all of the relationships are properly 
2. Make sure column names are marked as null vs. not null.
3. Make sure entities that are considered weak properly cascade when a record from the strong entity is deleted.


### Deliverable 2 - Database querying (15 Points)
For this Deliverable, you will insert data and query your database. You will need to demonstrate your ability to query from each table in your database. Create a file called **assignment2.sql** and add the following queries into the file.  You will need to take a screenshot of the rendered output for each command and place a screenshot of your output beneath each of the queries you identify.  Make sure to place a SQL comment above each command identifying the query.  Whether you create the database schema using the database modeling tool in MySQL workbench or by some other means, you will need to provide the commands used to create the database and related tables.   In order to make changes to the data, you may need to change the SQL Editor settings.  You can do this by navigating to EDIT -> SQL Editor -> and unchecking Safe Updates.  It is advised to restart MySQL Workbench after changing this setting.

#### Listed below is a list of requirements for this deliverable
1. Each table should consist of 5 or more records.  Make sure to include the insert queries in your assignment2.sql file
2. Three different SELECT statements that query each table in your database.  
3. Demonstrate your ability to perform a JOIN statement
 

## Submission Guidelines

For this assignment, you will submit 2 items to the repository that has been assigned to you.  The two items that you will need to submit are listed below: 
1. The README.MD file that includes screenshots of the result grid window for each SQL query
   1. Include the image beneath each query.
   2. The **assignment2.sql** file.  The assignment2.sql file should be 
      uploaded to your repository

Once you have completed both of the items above, you will need to submit the link to your repository for assignment 3 prior to the due date and time listed.  Make sure you receive an email confirmation notifying you that the assignment has been submitted.


## Lab Resources
- [W3 Schools SQL tutorial](https://www.w3schools.com/sql/)
- [Make a ReadMe file Web-based Editor](https://www.makeareadme.com/)
