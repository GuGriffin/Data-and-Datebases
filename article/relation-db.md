

Relational database
=====

1 Definition
----
A relational database** is a database that is based on a relational model (mathematical model).**

A relational model is a so-called relational model and has three aspects:

 - data structure: the form in which the data is stored, a two-dimensional table (rows and columns);
 - set of operating instructions: all SQL statements;
 - integrity constraints: constraints on the data within a table (field to field) and between tables (foreign keys).

2 Design
----

 - Database: Analysis of the data requirements to be stored. If it is a type of data (entity), it should be designed as a two-dimensional table.
 - Two-dimensional table: It consists of a header (field name, which specifies the name of the data) and a data (the actual stored content) section.

Here, special attention needs to be paid:**If the corresponding field value in the table is empty, the system will still allocate storage space for it**. This is the reason why relational databases are relatively wasteful of space!

3 Explanation of keywords
-----

 - DB: Database;
 - DBMS: Database Management System;
 - DBS: Database System = DBMS + DB;
 - DBA: Database Administrator.
 - Row/record: `row/record`, both essentially refer to a row (record) in a table. Row refers to the structural perspective, while record refers to the data perspective.
 - Column/field: `column/field`, both essentially refer to a column (a field) in a table. A column is considered from a structural perspective, while a field is considered from a data perspective.

4 SQL
-----

SQL: Structured Query Language, structured query language (data is query-oriented, and 99% of operations are query operations).

SQL is mainly divided into three types:

- DDL: Data Definition Language, used to maintain the structure of stored data (database, table), and the representative commands are `create`, `drop` and `alter` etc.
 - DML: Data Manipulation Language, used to manipulate data (the contents of tables). The representative commands are `insert`, `delete` and `update`, etc. However, within DML, there is a separate classification, namely DQL (Data Query Language), the representative command of which is `select`.
 - DCL: Data Control Language, which is mainly responsible for (user) rights management, with commands such as `grant` and `revoke`.

SQL is the operating command for relational databases, which is a kind of constraint, but not mandatory, similar to W3C. Therefore, this means that there may be some minor differences within different database products (such as Oracle and MySQL).

