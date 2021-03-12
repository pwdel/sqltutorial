# SQL Tutorial

## Intro

[Sequence Query Language](https://en.wikipedia.org/wiki/SQL) is a type of staticaly typed language for relational databases governed by [ISO 63555](https://www.iso.org/standard/63555.html).

## SQL Tutorial Links

[W3Schools](https://www.w3schools.com/sql/sql_intro.asp) has a basic SQL Tutorial.

## SQL Syntax

* Note that statements are not case sensitive.
* Note that semicolon ";" is required.

### SELECT

    SELECT - extracts data from a database table.

SELECT is the most basic command in SQL. Given a tablename, you can select entire tables, for example, for table name, "Customers:

```
SELECT * FROM Customers
```
This will display the entire table.

### SELECT DISTINCT

This extracts a specific column from a database table.

```
SELECT DISTINCT Country FROM Customers;
```

Will select a column of countries based upon the table Customers.

### WHERE

Where can filter a table based upon a condition. For example if you know the CustomerID of a particular customer, you can do:

```
SELECT * FROM Customers WHERE CustomerID = 1;
```
Which will display the corresponding row for that customer.


### UPDATE

    UPDATE - updates data in a database
    
### DELETE

    DELETE - deletes data from a database
    
### INSERT INTO

    INSERT INTO - inserts new data into a database
    
### CREATE DATABASE

    CREATE DATABASE - creates a new database
    
### ALTER DATABASE

    ALTER DATABASE - modifies a database
    
### CREATE TABLE    
    
    CREATE TABLE - creates a new table
    
### ALTER TABLE

    ALTER TABLE - modifies a table

### DROP TABLE
    
    DROP TABLE - deletes a table
    
### CREATE INDEX    
    
    CREATE INDEX - creates an index (search key)
    
### DROP INDEX

    DROP INDEX - deletes an index

