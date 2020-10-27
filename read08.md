# SQL


## What is SQL?
#### 'Structured Query Language' : it is a languages which allows dealing with database for the tech. users and non-tech. there are many common SQL such as mySQL and SQLite.

## Relational databases
#### it is a collection of related (two-dimensional) tables, just like the excel sheets but with a fixed number of columns but with flexibile row of data.

![ LOOK! ](https://www.sqlshack.com/wp-content/uploads/2019/12/create-a-view-in-sql-for-a-singe-table.png)


#### so the main purpose of learning SQL is to work with data and statistics so you could know and extract some data when required such as a number of cars that have less than 4 wheel in a certain region and so on ..



## SELECT queries 101
#### we use SELECT to get data from the database which most of times refers to a query, so to select a query for certain columns : 

    SELECT column, another_column, …
    FROM 'table's name'; </br>

#### but if you need all of them then you will need to select it like this example : 

    SELECT * 
    FROM 'table's name'; </br>



## Queries with constraints

#### this is will be good to control the number of rows because you may need some specific data from a multi-hundred rows. so in this part you will need "WHERE". its added after the FROM line and it will be followed with the condition that you want to perform. also you may use AND/OR as a logical operators. and there is other operators that SQL provide to deal with data such as (=,!=,LIKE,NOT LIKE,% ...etc)



## Filtering and sorting Query results

* use the 'DISTINCT' keyword to discard rows that have a duplicate column value. Ex:

    SELECT DISTINCT column, another_column, …
    FROM mytable
    WHERE condition(s); </br>

* GROUP BY keyword use to discard duplicates based on specific columns.
* ORDER BY clause is specified, each row is sorted alpha-numerically based on the specified column's value. In some databases
* INSERT statement declares which table to write into, the columns of data that we are filling, and one or more rows of data to insert
* DELETE statement describes the table to act on, and the rows of the table to delete through the WHERE clause.
* CREATE TABLE statement to create a new database table.
* ALTER TABLE statement to add, remove, or modify columns and table constraints.
* DROP TABLE statement it similaar to DELETE but it also removes the table schema from the database entirely.