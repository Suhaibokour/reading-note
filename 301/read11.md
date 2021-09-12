# Mongo and Mongoose

## What kind of data is a good fit for an SQL database?

* Choosing a database depends majorly on the type of data that your project needs to store. If your data is highly structured and associations among the program entities are clearly defined (for instance, if you are developing a point of sale system where you need to store customer orders and product records), conventional SQL based databases are the best fit.

## What kind of data is a good fit a NoSQL database?

* NoSQL databases can be classified on the basis of way of storing data as graph databases, key-value store databases, document store databases, column store database and XML databases.

## What does SQL stand for? 

* Structure Query language.

## What is a relational database? 

* A relational database is a type of database that stores and provides access to data points that are related to one another.

## What type of structure does a relational database work with?

* Relational databases are based on the relational model, an intuitive, straightforward way of representing data in tables. In a relational database, each row in the table is a record with a unique ID called the key.


##  NoSQL databases: Pros and cons

1. Pros

* Scalable and highly available: Many NoSQL databases are designed to support seamless, online horizontal scalability without significant single points of failure.
Flexible data models: Most non-relational systems do not require developers to make up-front commitments to data models. Existing schemas are dynamic, so they can often be changed “on the fly.”
 Dynamic schema for unstructured data: Documents can be created without a defined structure first, which enables each to have its own unique structure.  Syntax varies per database and fields can be added as you build the document.
High performance: A limited database functionality range (e.g., by relaxing durability guarantees) enables high performance amongst many NoSQL databases.
High-level data abstractions: Beyond the "value in a cell" data model, NoSQL systems provide high-level APIs for powerful data structures. For example, Redis includes a native-sorted set abstraction.

2. Cons

* Vague interpretations of ACID constraints: Despite the widespread belief that it supports NoSQL systems, ACID interpretations can be too broad to make clear determinations about database semantics.
Distributed systems have distributed systems problems: Though not specific to NoSQL systems, encountering such problems is common amongst NoSQL developers and may require SME troubleshooting.
 Lack of flexibility in access patterns: Without the abstraction found in relational databases, the on-disk representation of data leaks into the application's queries and leaves no room for NoSQL engines to optimize queries.

 ---

## What is OAuth?

* OAuth is an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential. In authentication parlance, this is known as secure, third-party, user-agent, delegated authorization. (OAuth only works using HTTPS)

## Give an example of what using OAuth would look like.

* when you go to log onto a website and it offers one or more opportunities to log on using another website’s/service’s logon. You then click on the button linked to the other website, the other website authenticates you, and the website you were originally connecting to logs you on itself afterward using permission gained from the second website.


## 


