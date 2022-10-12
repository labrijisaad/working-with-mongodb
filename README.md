# Basics of MongoDB 🥭 `🚧 In progress... 🚧`
>In this repository, I covered the basics of MongoDB 🥭


## Definition 
MongoDB is a rich open-source document-oriented and one of the widely recognised NoSQL database. It is written in C++ programming language.


## Overview of MongoDB 
- MongoDB is a document and a NoSQL database
- MongoDB supports various data types 
- Documents provide a flexible way of storing data 
- MongoDB documents of a similar type are grouped into collections 
- MongoDB models data as you read/write, brings structured or unstructured data, and provides high availability 
- MongoDB can be used for a variety of purposes because of the flexibility of storing structured or unstructured data


## Important Terms & Methods

<details>
<summary><b>Database</b></summary>
Database is a physical container for collections. Each database gets its own set of files on the file system. A single MongoDB server typically has multiple databases.
</details>

<details>
<summary><b>Collection</b></summary>
Collection is a group of documents and is similar to an RDBMS table. A collection exists within a single database. Collections do not enforce a schema. Documents within a collection can have different fields.
</details>


<details>
<summary><b>Document</b></summary>
A document is a set of key-value pairs. Documents have dynamic schema. Dynamic schema means that documents in the same collection do not need to have the same set of fields or structure, and common fields in a collection’s documents may hold different types of data.
</details>

<details>
<summary><b>Data Types</b></summary>

MongoDB supports many datatypes such as:
- String − This is the most commonly used datatype to store the data. String in MongoDB must be UTF-8 valid.
- Integer − This type is used to store a numerical value. Integer can be 32 bit or 64 bit depending upon your server.
- Boolean − This type is used to store a boolean (true/ false) value.
- Double − This type is used to store floating point values.
- Min/ Max keys − This type is used to compare a value against the lowest and highest BSON elements.
- Arrays − This type is used to store arrays or list or multiple values into one key.
- Timestamp − ctimestamp. This can be handy for recording when a document has been modified or added.
- Object − This datatype is used for embedded documents.
- Null − This type is used to store a Null value.
- Symbol − This datatype is used identically to a string; however, it’s generally reserved for languages that use a specific symbol type.
- Date − This datatype is used to store the current date or time in UNIX time format. You can specify your own date time by creating object of Date and passing day, month, year into it.
- Object ID − This datatype is used to store the document’s ID.
- Binary data − This datatype is used to store binary data.
- Code − This datatype is used to store JavaScript code into the document.
- Regular expression − This datatype is used to store regular expression.
</details>

<details>
<summary><b>CRUD operations</b></summary>

- The Mongo shell is an interactive command line tool provided by MongoDB to interact with your databases.
- To use the Mongo shell, we first need to make a connection to our cluster via a connection string.
- We use ‘show dbs’ to list databases, ‘use databasename’ to select a database, and ‘show collections’ to list collections in a database. 
- CRUD operations consist of Create, Read, Update, and Delete: Useful functions include insertOne, insertMany, findOne, find, count, replace, updateOne, updateMany, deleteOne, and deleteMany.

</details>

<details>
<summary><b>Indexes in MongoDB</b></summary>

- MongoDB stores an index as a tree to make finding documents more efficient.
- Indexes help quickly locate data without looking for it everywhere.
- Indexes should be created for the most frequent queries. 
- A compound index indexes more than one field.
- MongoDB stores data being indexed on the index entry and a location of the document on disk.
</details>

<details>
<summary><b>Aggregation Framework in MongoDB</b></summary>

- Using an aggregation framework, we can perform complex analysis on the data in MongoDB. 
- We can build our aggregation process in stages such as match, group, project, and sort.
- The outcome of an aggregation process can be queried or stored into another collection using `$merge`.
</details>

<details>
<summary><b>Replication & Sharding </b></summary>

- `Data replication` is the process of making multiple copies of data and storing them at different locations for backup purposes.
- `Database sharding` is the process of storing a large database across multiple machines.
- Replication is duplication of data and any changes made to the data. 
- Replication provides fault tolerance, redundancy, and high availability for your data.
- Replication will not prevent a disaster such as the deletion of documents, collections, or even databases. 
- For those human errors, we have backups.
- For growing data sets, you can use Sharding to scale horizontally.
</details>

<details>
<summary><b>Accessing MongoDB from Python</b></summary>

- MongoClient is a class that helps you interact with MongoDB.
- MongoClient is imported from pymongo, the official MongoDB driver for Python. 
- We can perform single or bulk inserts. We can replace whole documents
- We can perform an in-place update, which is a preferred option.
- And we can delete one or more documents from our collection.
</details>








## Advantages of MongoDB

- The database schema can be flexible when working with MongoDB. 
- We can change it as needed without involving complex data definition language statements. 
- MongoDB uses a **code-first approach**, instead of a design then code approach. 
- MongoDB also utilizes an **evolving schema**. 
- Complex data analysis can be done on the server using Aggregation Pipelines. 
- MongoDB provides native **high availability**.
- MongoDB can be used in a variety of use cases.
- The **scalability** MongoDB provides makes it easier to work across the globe And it enables us to perform **real-time analysis** on data.


## 🥭 MongoDB Labs 🧪
- [Lab 1 - Getting Started](https://github.com/labrijisaad/working-with-mongodb/blob/main/Labs/lab-1.md)
- [Lab 2 - CRUD operations](https://github.com/labrijisaad/working-with-mongodb/blob/main/Labs/lab-2.md)
- [Lab 3 - MongoDb Indexing](https://github.com/labrijisaad/working-with-mongodb/blob/main/Labs/lab-3.md)
- [Lab 4 - MongoDB Aggregation](https://github.com/labrijisaad/working-with-mongodb/blob/main/Labs/lab-4.md)
- [Lab 5 - Accessing MongoDB from Python](https://github.com/labrijisaad/working-with-mongodb/blob/main/Labs/lab-5.md)


## Reference
- [All Basics of MongoDB](https://medium.com/nerd-for-tech/all-basics-of-mongodb-in-10-minutes-baddaf6b6625)


## Author
<a href="https://www.linkedin.com/in/labrijisaad/" target="_blank">Saad LABRIJI</a>


## Change Log
| Date (YYYY-MM-DD) | Version | Changed By    | Change Description                                 |
| ----------------- | ------- | ------------- | -------------------------------------------------- |
| 2022-10-10        |   --    | Labriji saad  | Created the project                                |
| 2022-10-11        |   --    | Labriji saad  | Added Lab-1                                        |
| 2022-10-12        |   --    | Labriji saad  | Added Lab-2                                        |
| 2022-10-12        |   --    | Labriji saad  | Added Lab-3                                        |



