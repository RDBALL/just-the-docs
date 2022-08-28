---
layout: default
title: Code 301 | Class 11
parent: Code 301 Notes
---

### [nosql vs sql](https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool)

### Fill in the chart below with five differences between SQL and NoSQL databases

| SQL 	| NoSQL 	|
|---	|---	|
|  Vertically Scalable 	| Horizontally Scalable 	|
|  Relational Database 	|  Non-relational database 	|
|  Table Based 	| Document based 	|
|  Predefined scheme 	| Dynamic schema for unstructured data 	|
| More suited for complex query intensive environments 	| No standard interface to perform complex queries 	|

### What kind of data is a good fit for an SQL database?

* Complex transactional data is a good fit for the vertical scaling structure of SQL

### Give a real world example

* Large corporations such as netflix and amazon use SQL databases to conduct data analysis on users

### What kind of data is a good fit for a NoSQL database?

* Large unstructured data that can be dynamically entered

### Give a real world example

* YouTube uses a NoSQL database for storing large files such as videos

### Which type of database is best for hierarchical data storage?

* NoSQL databases are best used for hierarchical data storage sue to being able to traverse a file tree-like structure when accessing data that branches from the parent / root node.

### Which type of database is best for scalability?

* Both are able to be scaled but NoSQL, by the nature of how they are structured, can be scaled by adding additional servers to the database and are not as limited by hardware requirements like SQL databases.

### [Video sql vs nosql](https://www.youtube.com/watch?v=ZS_kXvOeQ5Y)

### What does SQL stand for?

* Structured Query Language

### What is a relational database?

* A relational database is structured with a preset schema to ensure that data is entered in a recognizable, formatted style.

### What type of structure does a relational database work with?

* A relational database uses one, pre-defined file structure.

### What is a ‘schema’?

* The representational plan of an outline

### What is a NoSQL database?

* A NoSQL database is structured horizontally with the ability to store data that does not use a fixed format

### How does it work?

* There are four major types of NoSQL databases that are widely used

* **Document databases** store data in documents similar to JSON (JavaScript Object Notation) objects. Each document contains pairs of fields and values. The values can typically be a variety of types including things like strings, numbers, booleans, arrays, or objects.

* **Key-value databases** are a simpler type of database where each item contains keys and values.

* **Wide-column stores** store data in tables, rows, and dynamic columns.

* **Graph databases** store data in nodes and edges. Nodes typically store information about people, places, and things, while edges store information about the relationships between the nodes.

[mongodb](https://www.mongodb.com/nosql-explained)

### What is inside of a Mongo database?

* MongoDB is populated with BSON files which stands for Binary Object Notation. This is a binary form representing simple or complex data structures

### Which is more flexible - SQL or MongoDB? and why

* A MongoDB is more flexible as it ensures a high availability of diverse data over SQL which uses the  ACID (Atomicity, Consistency, Isolation, and Durability) properties and ensures greater reliability of transactions.

### What is the disadvantage of a NoSQL database?

* NoSQL databases do not have the reliability functions that are present within SQL databases.

***Bookmark and Review***

[mongoose api](https://mongoosejs.com/docs/api.html#Model)

[React Router](https://reactrouter.com/web/api/BrowserRouter)
