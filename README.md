# Basics of MongoDB 🥭 `🚧 In progress... 🚧`
>In this repository, I covered the basics of MongoDB 🥭


## Definition 
> MongoDB is a rich open-source document-oriented and one of the widely recognised NoSQL database. It is written in C++ programming language.


## Overview of MongoDB 
- MongoDB is a document and a NoSQL database
- MongoDB supports various data types 
- Documents provide a flexible way of storing data 
- MongoDB documents of a similar type are grouped into collections 
- MongoDB models data as you read/write, brings structured or unstructured data, and provides high availability 
- MongoDB can be used for a variety of purposes because of the flexibility of storing structured or unstructured data


## Important Terms
>### Database
Database is a physical container for collections. Each database gets its own set of files on the file system. A single MongoDB server typically has multiple databases.

>### Collection
Collection is a group of documents and is similar to an RDBMS table. A collection exists within a single database. Collections do not enforce a schema. Documents within a collection can have different fields.

>### Document
A document is a set of key-value pairs. Documents have dynamic schema. Dynamic schema means that documents in the same collection do not need to have the same set of fields or structure, and common fields in a collection’s documents may hold different types of data.

>### Data Types
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


## Advantages of MongoDB

- The database schema can be flexible when working with MongoDB. 
- We can change it as needed without involving complex data definition language statements. 
- MongoDB uses a **code-first approach**, instead of a design then code approach. 
- MongoDB also utilizes an **evolving schema**. 
- Complex data analysis can be done on the server using Aggregation Pipelines. 
- MongoDB provides native **high availability**.
- MongoDB can be used in a variety of use cases.
- The **scalability** MongoDB provides makes it easier to work across the globe And it enables us to perform **real-time analysis** on data.

















## Reference
- [All Basics of MongoDB](https://medium.com/nerd-for-tech/all-basics-of-mongodb-in-10-minutes-baddaf6b6625)

