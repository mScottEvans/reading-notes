Readings: Mongo and Mongoose

SQL vs noSQL
5 Differences-

- SQL databases are relational, NoSQL databases are non-relational.
- SQL databases use structured query language and have a predefined schema. NoSQL databases have dynamic schemas for unstructured data.
- SQL databases are vertically scalable, while NoSQL databases are horizontally scalable.
- SQL databases are table-based, while NoSQL databases are document, key-value, graph, or wide-column stores.
- SQL databases are better for multi-row transactions, while NoSQL is better for unstructured data like documents or JSON.





- What kind of data is a good fit for an SQL database?
If your data is highly structured and associations among the program entities are clearly defined (for instance, if you are developing a point of sale system where you need to store customer orders and product records), conventional SQL based databases are the best fit.
- Give a real world example.
if you are developing a point of sale system where you need to store customer orders and product records
- What kind of data is a good fit a NoSQL database?
High velocity transactions
they are a good fit with modern Agile development practices based on sprints, quick iterations, and frequent code pushes.
- Give a real world example.
- Which type of database is best for hierarchical data storage?
Document based database like MongoDB, and Redis are great for small scale, hierarchical data with a relatively small amount of children for each entry.
- Which type of database is best for scalability?
MySQL and MongoDB. While MongoDB is often considered an alternative to MySQL, the two databases do work well together when properly designed.



- What does SQL stand for?
Structured Query Language
- What is a relational database?
a database structured to recognize relations among stored items of information.
- What type of structure does a relational database work with?
The relational model means that the logical data structures—the data tables, views, and indexes—are separate from the physical storage structures.
- What is a ‘schema’?
A simple schema is just a map of keys and types: That's the same as using a type property: A schema can also be a map between keys and default values
- What is a NoSQL database?
are non-tabular databases and store data differently than relational tables. NoSQL databases come in a variety of types based on their data model.
- How does it work?
NoSQL is a database system which doesn't use string based SQL queries to fetch data. Instead you build queries using an API they will provide, for example Amazon DynamoDB is a good example of a NoSQL database.
- What is inside of a Mongo database?
MongoDB stores data records as documents (specifically BSON documents) which are gathered together in collections. A database stores one or more collections of documents.
- Which is more flexible - SQL or MongoDB? and why.
While MongoDB is more flexible and ensures high and diverse data availability, a SQL Database operates with the ACID (Atomicity, Consistency, Isolation, and Durability) properties and ensures greater reliability of transactions.
- What is the disadvantage of a NoSQL database?
Compatibility issues with SQL instructions. New databases use their own characteristics in the query language and they're not yet 100% compatible with the SQL used in relational databases.


References: https://www.integrate.io/blog/the-sql-vs-nosql-difference/

https://medium.com/@albertjamesteddy/hierarchical-data-why-not-mongodb-42eb5777c243#:~:text=Document%20based%20database%20like%20MongoDB,of%20children%20for%20each%20entry.

https://hevodata.com/learn/mongodb-vs-sql/#:~:text=SQL%20Databases%20Record&text=While%20MongoDB%20is%20more%20flexible,ensures%20greater%20reliability%20of%20transactions.
