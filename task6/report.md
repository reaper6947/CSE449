link : https://www.udemy.com/course/database-engines-crash-course/
these are the topics that i have learned from this course 
## Table of Contents

** ACID Properties **
**Database Indexing**
**Database Partitioning**
**Database Replication**
**Database Sharding**
**Database Cursors**
**Concurrency Control **
**B-Trees in Production Database Systems**
**Database System Designs**
**Database Engines **
**Database Security**


 <hr>
 
** ACID Properties **

* Atomicity refers to the idea that a database transaction is either completed in its entirety or not completed at all. This ensures that if one part of the transaction fails, the entire transaction will be rolled back and the database will be left in a consistent state.
* Consistency ensures that any transaction that is completed will bring the database from one consistent state to another. This means that if a transaction is completed, it will not violate any of the defined rules or constraints of the database.
* Isolation ensures that multiple transactions can be completed concurrently without interfering with each other. This is important because it allows multiple users to access and update the database at the same time without causing conflicts.
* Durability ensures that once a transaction is completed and committed to the database, it will not be lost even in the event of a power failure or other system crash.

**Database Indexing**
* Indexing is a way of organizing data in a database to make it more efficient to search and retrieve. It involves creating a separate data structure that is used to point to the location of specific records in the database.

**Database Partitioning**
* Partitioning is a technique used to divide a large database into smaller, more manageable pieces called partitions. This can improve the performance and scalability of a database by allowing it to be accessed and updated more efficiently.

**Database Replication**
* Replication is a technique used to create copies of a database on multiple servers. This can improve the reliability and availability of the database, as it allows for the continued operation of the database even if one of the servers fails.

**Database Sharding**
* Sharding is a technique used to horizontally partition a large database into smaller pieces called shards. Each shard is stored on a separate server, and the data is distributed across the servers. This can improve the performance and scalability of the database by allowing it to handle more requests simultaneously.

**Database Cursors**
* Cursors are a way of processing large amounts of data in a database one row at a time. They allow you to define a result set and then iterate through it one row at a time, performing some action on each row as you go. This can be useful when working with large datasets because it allows you to process the data in smaller chunks rather than all at once.

**Concurrency Control **
* Concurrency control is a technique used to ensure that multiple transactions can be completed concurrently without conflicting with each other. This is important because it allows multiple users to access and update the database at the same time without causing conflicts.

**B-Trees in Production Database Systems**
* B-Trees are a type of data structure used in production database systems to store and retrieve data efficiently. B-trees are used in indexes to improve the performance of database queries, and are well-suited to handling large amounts of data.

**Database System Designs**
* A database system design is a blueprint for organizing and storing data in a database. It includes the logical and physical design of the database, as well as the database management system (DBMS) used to access and manipulate the data. A well-designed database system can make it easier to store, retrieve, and analyze data, and can help ensure the integrity and security of the data.

**Database Engines **
* A database engine is a software that is responsible for storing, processing, and securing data stored in a database. There are various types of database engines, including relational database management systems (RDBMS), object-oriented database management systems (OODBMS), and NoSQL database management systems.

**Database Security**
* Database security is the process of protecting a database from unauthorized access, use, disclosure, disruption, modification, or destruction. It is an important aspect of information security and is necessary to protect sensitive and confidential information stored in databases.




