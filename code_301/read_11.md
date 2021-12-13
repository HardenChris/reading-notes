# Mongo and Mongoose

## NoSQL vs SQL

| SQL                                                                                       | NoSQL                                                                                     |
|------------------------------------------------------------------------------------------ |------------------------------------------------------------------------------------------ |
| SQL database are called Relational Database (RDBMS)                                       | NoSQL are called non-relational/distributed database.                                     |
| SQL databases are based on tables                                                         | NoSQL is based on document-based, graph databases, key-value pairs, wide-column stores.  |
| SQL databases have a predefined schema                                                    | NoSQL is a dynamic schema for data that is unstructured.                                  |
| SQL databases are scaled vertically                                                       | NoSQL which is scaled horizontally.                                                       |
| SQL databases use Structured Query Language (SQL) for manipulating and defining the data  | NoSQL queries are focused on collections of documents.                                    |

* What kind of data is a good fit for an SQL database?
  * data which is displayed as numbers and rows or heavy-duty transactional type applications.

* Give a real-world example.
  * MySQL Community Edition, Oracle Express Edition, MS-SQL Server Express Edition

* What kind of data is a good fit for a NoSQL database?
  * hierarchical data that follows key-value pairs like a JSON

* Give a real-world example.
  * MongoDB & CouchDB

* Which type of database is best for hierarchical data storage?
  * NoSQL

* Which type of database is best for scalability?
  * Vertically SQL, horizontally NoSQL

## SQL vs NoSQL

* What does SQL stand for?
  * Structured Query Language - ex: `SELECT id, name, price FROM products`

* What is a relational database?
  * works with certain assumptions or pre-designed setup

* What type of structure does a relational database work with?
  * relational schema like 'one-to-one', 'one-to-many', 'many-to-many'

* What is a ‘schema’?
  * data layout & design

* What is a NoSQL database?
  * stores data in a database, which has collections, which store documents. There is no set schema. No relations

* How does it work?
  * fewer relation data but still access and flexibility

* What is inside of a Mongo database?
  * Database, Collections, Documents

* Which is more flexible - SQL or MongoDB? and why.
  * SQL has a schema that makes it easy to use but SQL has fewer rules.

* What is the disadvantage of a NoSQL database?
  * No relations can have different levels of data compared to other data around it.

## Things I want to know more about

Issac, Luke P "SQL vs NoSQL Database Differences Explained with few Example DB" thegeekstuff, 14 Jan 2014, <https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool>

"SQL vs NoSQL or MySQL vs MongoDB" YouTube, uploaded by Academind, 25 July 2018, <https://www.youtube.com/watch?v=ZS_kXvOeQ5Y>.

All definitions and information came from the above-listed publication(s).

[<===Back>](README.md)
