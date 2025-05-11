1. DDL (Data Definition Language)
   - CREATE: Used to create tables, databases, indexes, and other objects.---create table employee
   - ALTER: Used to modify existing database structures.--ALTER TABLE Employees ADD Email VARCHAR(255);
   - DROP: Deletes tables, databases, indexes,---DROP TABLE Employees;
   - TRUNCATE: Removes all records from a table without logging individual row deletions.-TRUNCATE TABLE table_name;
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
     - Created using CREATE VIEW statement.
   - Index: Improves database performance by allowing faster data retrieval.
     - Created using CREATE INDEX statement.
    


















..


.
