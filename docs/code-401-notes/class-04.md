---
layout: default
title: Code 401 | Class 04
parent: Code 401 Notes
---

### Readings: Data Modeling

#### [nosql vs sql](https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool)

#### What type of database is the best fit for the complex query intensive environment?

* A SQL database will be able to handle complex queries due to the fact that SQL databases are constrained in regards to a set schema which correlates to set query parameters.

#### What type of database is the best fit for hierarchical data storage?

* A NoSQL database is a good fit for hierarchical data

#### Describe the differences in scalability between a SQl and NoSQL database as though you were speaking to a non-technical friend

* A SQL database has the ability to scale vertically where a NoSQL database can scale horizontally.

#### [sql modeling techniques](https://www.essentialsql.com/get-ready-to-learn-sql-7-simplified-data-modeling/)

#### Among data tables, what is a one-to-many relationship and how do we “relate” them?

* This is when data from one table may relate to data in multiple other tables. They are related through like items.

#### Prior to designing your relational database, it might be useful to ___a___ of the database tables and their relationships

* It may be useful to create a diagram to visualize the database tables and their relationships

#### Explain the difference between a primary and foreign key

* Primary key: Primary key is the general term for any set of values that are unique and non-null across a table.  They provide a means to identify one record in a table.  A compound primary key is a primary key made up of two or more columns.

* Foreign key: A foreign key is a set of values in a table which match to the primary key of another table.  There isn’t a command to define a foreign key, per se, the existence of columns with the proper data is the minimum requirement.

### Videos

[sql vs nosql](https://www.youtube.com/watch?v=ZS_kXvOeQ5Y)

#### How do we treat keywords and parameters differently in SQL syntax?

* Keywords: these are words that have defined meaning within SQL. They are used in queries when identifying what type of data needs to be pulled

* Parameters: these are used in data exchange between the database and the requesting client.

#### Define normalization within the context of schemas and data

* Normalization will allow the database to be more user and dev friendly when it comes to making queries and also providing future database expansion.

#### Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter

* A one to one data relationship means that one data table is directly linked to a secondary data table. An example of this would be a university as one data table and the student body being separate individual data tables. The university data table holds a one to one relationship with every student body data table.

* A one to many relationship is a data table that holds values that can be linked to other, independent data tables. An example would be a university student class schedule on one data table, from that table you can link to many other student data tables by connecting individual classes that are shared between the student data tables.

### Bookmark and Review

[sequelize api](https://sequelize.org/master/)
