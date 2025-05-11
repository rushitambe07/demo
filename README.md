*Placemates is a centralized platform that helps student to connect with previously placed alumni.
-The idea came to me as I faced problems in third year.We almost missed our first three years due to pandemic
-so we were not aware of how placements would be work in our college or what should we study for placements.
-bascailycy My classmates also facing the same issue, so we developed the Placemates website.
Technologies used: React, Express, Node, and MySQL.
The main functionality of the website is that members from the campus TNP section can add informati related to recruiters,
such as their names, which domain they hiring,the packages they offer.info about alumni who placed in previous batches,
such as their names, the companies they were placed in, the roles and packages they have and their contact details
- With this information, students can prepare for placements,get idea about the companies hiring from our campus,
-  and connect with placed alumni and understand the hiring process.
-  company =id,company name,package,branch,10TH,12TH,skill,location,graduction,job description
-  alumini= id,name,branch, batch,company,package,contack no,email,url,
-  user= id, user,branch,passwoed,email.rollno

*CricScore is a Chrome extension that provides the cricket score. I have always been excited about how extensions actually work,
and I was also a beginner in web development, so I developed CricScore. HTML, CSS, JavaScript are the technologies used to develop it.

*BlazeBuy:  The e-commerce cart project is designed to provide users with an efficient and simple shopping experience. 
-It allows users to add, remove, and manage items in their cart, adjust quantities, and view price calculations.
The technology used is HTML,CSS,JavaScript. The project features a responsive design, making it accessible on both mobile and desktop.
-providing a smooth and reliable shopping experience for users while offering easy management for admins.

* Normalazation = The purpose of normalization is to reduce the complexity of the database
    -Normalization in SQL is the process of organizing data to reduce redundancy and improve data integrity.
    -It involves breaking down large tables into smaller.
   - 1NF-it Ensures that each column contains atomic values (no repeating groups).

 *      DROP	                                     DELETE	                     TRUNCATE
   drop delete the entire table.	   it delete rows of a table.   it delete all the rows of a table at once.
   data not restored by rollback 	data can restored rollback.  data not restored using rollback command.

*ACID
    Atomicity- All steps in a transaction must succeed or none of them.
    consistency-The database correct valid before and after a transaction.
    ioslation- Transactions not interfere with each other.
    durability - once transaction is saved it  saved—even if the system crashes

1. DDL (Data Definition Language)
   - CREATE: Used to create tables, databases, indexes, and other objects.---create table employee
   - ALTER: Used to modify existing database structures.--ALTER TABLE Employees ADD Email VARCHAR(255);
   - DROP: Deletes tables, databases, indexes,---DROP TABLE Employees;
   - TRUNCATE: Removes all records from a table without logging individual row deletions.-TRUNCATE TABLE;
   - RENAME: Changes the name of an existing database object.---ALTER TABLE Employees RENAME TO Staff;

2. DML (Data Manipulation Language)
   - SELECT: Retrieves data from a database.  ---- select * from tablename;
   - INSERT: Adds new records to a table.     ---- insert into tablename(id)values(1);
   - UPDATE: Modifies existing records in a table. ----update tablename set age=20 where age=12;
   - DELETE: Removes records from a table.----DELETE FROM table_name WHERE condition;

3. DCL (Data Control Language)
   - GRANT: Provides specific privileges to users.
   - REVOKE: Removes privileges from users.

4. TCL (Transaction Control Language)
   - COMMIT: Saves all changes made by the transaction.
   - ROLLBACK: Reverts changes made by the transaction.
   - SAVEPOINT: Creates a point in a transaction to which you can later roll back.

5. Understanding Constraints and Their Types
   - NOT NULL: Ensures a column cannot have a NULL value.
   - UNIQUE: Ensures all values in a column are unique.
   - PRIMARY KEY: Uniquely identifies each record in a table.
   - FOREIGN KEY: Ensures referential integrity between tables.
   - CHECK: Ensures that all values in a column satisfy a condition.
   - DEFAULT: Sets a default value for a column if no value is provided.

7. SQL Functions
   - Aggregate Functions: COUNT(), SUM(), AVG(), MIN(), MAX()
   - String Functions: CONCAT(), LENGTH(), UPPER(), LOWER(), SUBSTRING()
   - Date Functions: NOW(), CURDATE(), DATE_FORMAT()
   - Numeric Functions: ROUND(), CEIL(), FLOOR(), ABS()
   - Conversion Functions: CAST(), CONVERT()

8. Clauses in SQL
   - WHERE: Filters records based on conditions.
   - GROUP BY: Groups records with identical values.
   - HAVING: Filters groups based on conditions.
   - ORDER BY: Sorts the result set in ascending or descending order.
   - LIMIT: Restricts the number of records returned.

9. Joins and Their Types
   - INNER JOIN: Returns matching rows from both tables.
   - LEFT JOIN: Returns all rows from the left table and matching rows from the right table.
   - RIGHT JOIN: Returns all rows from the right table and matching rows from the left table.
   - FULL OUTER JOIN: Returns all rows when there is a match in either table.
   - SELF JOIN: A table joins itself.
   - CROSS JOIN: Returns the Cartesian product of both tables.

10. Sub-Queries
   - A query nested inside another query.
   - it is Used with SELECT, INSERT, UPDATE, DELETE.
   - it Can return single or multiple values.

11. Views and Indexes
   - View: A virtual table based on a query result.
     - Created using CREATE VIEW statement. -- create view view name as select from view;
   - Index: Improves database performance by allowing faster data retrieval.
     - Created using CREATE INDEX statement.
    










































































.
