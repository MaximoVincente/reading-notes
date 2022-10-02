# "Class 11" Reading Notes 📖

## NoSQL vs SQL

1. Fill in the chart below with five differences between SQL and NoSQL databases:
   - `SQL` databases are primarily called as Relational Databases (RDBMS).  
     - `NoSQL` database are primarily called as non-relational or distributed database.
   - `SQL` databases are table based databases whereas NoSQL databases are document based, key-value pairs, graph databases or wide-column stores. This means that SQL databases represent data in form of tables which consists of n number of rows of data.
     - `NoSQL` databases are the collection of key-value pair, documents, graph databases or wide-column stores which do not have standard schema definitions which it needs to adhered to.
   - `SQL` databases have predefined schema whereas NoSQL databases have dynamic schema for unstructured data.
   - SQL databases are vertically scalable.
     - `NoSQL` databases are horizontally scalable.
     - `SQL` databases are scaled by increasing the horse-power of the hardware.
       - `NoSQL` databases are scaled by increasing the databases servers in the pool of resources to reduce the load.
   - `SQL` databases uses SQL ( structured query language ) for defining and manipulating the data, which is very powerful.
     - In `NoSQL` database, queries are focused on collection of documents. Sometimes it is also called as UnQL (Unstructured Query Language). The syntax of using UnQL varies from database to database.

2. What kind of data is a good fit for an SQL database?
   - For complex queries: SQL databases are good fit for the complex query intensive environment whereas NoSQL databases are not good fit for complex queries.
3. Give a real world example.
   - My SQL
4. What kind of data is a good fit a NoSQL database?
   - NoSQL database fits better for the hierarchical data storage as it follows the key-value pair way of storing data similar to JSON data. NoSQL database are highly preferred for large data set (i.e for big data).
5. Give a real world example.
   - Hbase
6. Which type of database is best for hierarchical data storage?
   - NoSQL Database
7. Which type of database is best for scalability?
   - NoSQL

## sql vs nosql (video)

1. What does SQL stand for?
   - Structured Query Language
2. What is a relational database?
   - It means we have a database that works with certain assumptions or in a certain way, and it supports the sq language. Such data works with tables.
3. What type of structure does a relational database work with?
   - Structured query language.
4. What is a ‘schema’?
   - A schema of which data can go into a table and is defined by so-called fields,i.e., an id, a name, a price, and a description.
5. What is a NoSQL database?
   - NoSql has so-called collections database, that has documents, kind've like the rows in a table for SQL.
6. How does it work?
   - It has a database with so-called collections, and inside of the collections it has so-called documents, and don't have to have the same schema. There is no schema.
7. What is inside of a Mongo database?
   - Collections, documents.
8. Which is more flexible - SQL or MongoDB? and why.
   - MongoDB, you can have different documents be part of the same collection, because there is no schema. You can add new data.
9. What is the disadvantage of a NoSQL database?
   - You can have duplicate data if a product changes, you have to update the product collection but also in the orders collection.

## Things I want to learn more about

I want learn more about ralational database.

## References

- [SQL vs NoSQL](https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool)
- [SQL vs NoSQL video](https://www.youtube.com/watch?v=ZS_kXvOeQ5Y)
