# SQL
I study SQL and make notes

### SQL - Structured Query Language

#### Functions of SQL 
  1. SQL can execute queries against a database
  2. SQL can retrieve data from a database
  3. SQL can insert data to a database
  4. SQL can update in a database
  5. SQL can delete records from a database 
  6. SQL can create new database
  7. SQL can create new tables in a database
  8. SQL can create stored procedures in a database
  9. SQL can set permissions on tables, procedures and views 

Use of SQL: To build a website 

To build a website you need
  1. An RDBMS program
  2. Server-side scripting language 
  3. SQL to get the data from the database
  4. HTML/CSS to style the page 

![image](https://github.com/anikethj61/SQL/blob/main/SQL_1.png)

An RDBMS is a relational database management system which consists of tables that are related by some condition. These tables have fields essentially rows and columns.
A field is a column in a table that is designed to maintain a specific info about every record in the table. A record is the individual entry that exists in a table. A column is a vertical entity in a table. 

#### Important SQL commands 

```
SELECT 
UPDATE
DELETE
```

```
INSERT INTO
CREATE DATABASE
ALTER DATABSE
```

```
CREATE TABLE
ALTER TABLE
DROP TABLE
```

```
CREATE INDEX
DROP INDEX
```

##### SELECT
  SELECT <field> FROM <table_name>
  Eg: ``` SELECT CustomerName, City FROM Customers ```


##### SELECT DISTINCT
  SELECT DISTINCT <field(s)> FROM <table>
  Eg: SELECT DISTINCT Country FROM Customers
  SELECT COUNT (DISTINCT) FROM Customers

##### WHERE 
  A clause used to filter records. WHERE helps filter records that fulfil a specific condition. 
  Eg: SELECT <column(s)>
      FROM <table>
      WHERE condition

##### AND, OR and NOT operators 
  AND & OR filter records based on more than one condition
  NOT operator displays a record if the condition for that record is NOT TRUE 
  
Syntax
  ```
  SELECT <column>
  FROM <table>
  WHERE condition1 AND condition2 AND condition3
  ```
  ```
  SELECT <column>
  FROM <table>
  WHERE condition1 OR condition2
  ```
  ```
  SELECT <column>
  FROM <table>
  WHERE NOT condition1
  ```
