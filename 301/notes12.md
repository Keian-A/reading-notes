# Read-12

## Notes on [SQL vs NoSQL](https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool)

SQL:
- Primarily called relational databases
- Table based database
- Has pre-defined schema
- Vertically scalable
- Uses SQL: Structured Query Language

NoSQL:
- Primarily called non-relational or distributed database
- Document based database
- Dynamic structure for unstructured data
- Horizontally scalable
- Queries are found on a collection of documents (aka Unstructured Query Language)

1. What kind of data is a good fit for an SQL database?
  - SQL DBs are a good fit for complex queries
1. Give a real world example.
  - [MySQL database](https://www.thegeekstuff.com/2008/07/howto-install-mysql-on-linux/) is a very popular SQL database 
1. What kind of data is a good fit a NoSQL database?
  - Heirarchical data storage is great for NoSQL
1. Give a real world example.
  - [MongoDB](https://www.thegeekstuff.com/2013/01/install-mongodb/) is a very popular NoSQL database
1. Which type of database is best for hierarchical data storage?
  - NoSQL
1. Which type of database is best for scalability?
  - SQL is good for vertically scaling (better hardware), whereas NoSQL is good for horizontally scaling (more servers, or processing power)


## Notes on 

1. What does SQL stand for?
  - Structured Query Language
1. What is a realational database?
  - Multiple tables which can be identified with similar IDs
1. What type of structure does a relational database work with?
  - Data tables
1. What is a ‘schema’?
  - The structure or blueprint of how data is organized
1. What is a NoSQL database?
  - Non-relational database
1. How does it work?
  - There are collections, which house documents. This is like a nested object within another object
1. What is inside of a Mongo database?
  - Collections - the idea behind here is all the data you need is in one place
1. Which is more flexible - SQL or MongoDB? and why.
  - If you have a lot of data and update that data a lot, you might want to go with SQL. But if you have a lot of different data, you might want to go with NoSQL.
1. What is the disadvantage of a NoSQL database?
  - You have to update each collection every time a piece of data changes
      
[<-- Back](ToC.md)