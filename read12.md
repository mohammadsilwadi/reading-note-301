# [reading-note-301](https://mohammadsilwadi.github.io/reading-note-301/)

## nosql vs sql

| SQL        |   NoSQL  |
| ---------- | -----:|
|  Relational Databases     | non-relational  |
| table based databases      |   document based databasees|
|  predefined schema |   have dynamic schema |
|vertically scalable   | horizontally scalable  |
|scaled by increasing the horse-power of the hardware.| scaled by increasing the databases servers|

### What kind of data is a good fit for an SQL database?

If your data is highly structured and associations among the program entities are clearly defined

### Give a real world example

if you are developing a point of sale system where you need to store customer orders and product records ,conventional SQL based databases are the best fit.

### What kind of data is a good fit for an NoSQL database?

Semi-structured or Unstructured data / flexible schema. Limited pre-defined access paths and query patterns. No complex queries, stored procedures, or views. High velocity transactions.

### Give a real world example

Redis, Dynamo, Riak are some NoSQL examples of key-value store DataBases. They are all based on Amazon's Dynamo paper.

### Which type of database is best for hierarchical data storage?

 SQL databases

### Which type of database is best for scalability?

  SQL databases

### What does SQL stand for?

  Structured Query Language

### What is a realational database?

   a type of database that stores and provides access to data points that are related to one another

### What type of structure does a relational database work with?

provides access to data points that are related to one another.

### What is a ‘schema’?

 cognitive framework or concept that helps organize and interpret information

### What is a NoSQL database?

 NoSQL is a type of database that stores and retrieves data without needing to define its structure first

### How does it work?

database provides a mechanism for storage and retrieval of data that is modeled in means other than the tabular relations used in relational databases. ... NoSQL databases are increasingly used in big data and real-time web applications.

### What is inside of a Mongo database?

MongoDB stores data records as documents (specifically BSON documents) which are gathered together in collections. A database stores one or more collections of documents.

### Which is more flexible - SQL or MongoDB? and why

hile MongoDB is more flexible and ensures high and diverse data availability, a SQL Database operates with the ACID (Atomicity, Consistency, Isolation, and Durability) properties and ensures greater reliability of transactions.

### What is the disadvantage of a NoSQL database?

Disadvantages. NoSQL databases don't have the reliability functions which Relational Databases have (basically don't support ACID). This also means that NoSQL databases offer consistency in performance and scalability.
