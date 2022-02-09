# technical_paper_NoSQL

## NoSQL Database

Nosql database is a non relational database used for storing data and relational values.It does not require a fix schema. It avoids joins and easy to sacale.
Nosql genarally also called no- SQL . It is genrally faster than our Relational databases.The major purpose of using NoSQL is to deal with large set of data.Traditional RDBMS uses SQL syntax to store and retrieve data for further insights. Instead, a NoSQL database system encompasses a wide range of database technologies that can store structured, semi-structured, unstructured and polymorphic data. 
## Brief History of NoSQL
  1998- Carlo Strozzi use the term NoSQL for his lightweight, open-source relational database
  2000- Graph database Neo4j is launched<br>
  2004- Google BigTable is launched.<br>
  2005- CouchDB is launched.<br>
  2007- The research paper on Amazon Dynamo is released <br>
  2008- Facebooks open sources the Cassandra project <br>
  2009- The term NoSQL was reintroduced <br>
## Why NoSQL ?
The concept of NoSQL became popular with company having trouble storing large data set and their scalability.The system response time becomes slow when you use RDBMS for massive volumes of data and in the woorld of data set storage of these large data aren't cost effective in relational database.These large set of data came in all shapes and sizes — structured, semi-structured, and polymorphic — and defining the schema in advance became nearly impossible. NoSQL databases allow developers to store huge amounts of unstructured data, giving them a lot of flexibility than it counterparts.
## Some features of NoSQL
Some of the feature that NoSQL provide over RDBMS are
* Flexible
* Both horizontal and vertical scalibillity.
* Faster queries.
* Ease of use for developer.
* NoSQL databases never follow the relational model.
* Doesn’t require object-relational mapping and data normalization.
* Uses json file so data set does not have to follow schema.
* Do not require any sort of definition of the schema of the data.
* Does not have to follow ACID properties.<br>
**Simple API**
* Offers easy to use interfaces for storage and querying data provided.
* Low-level data manipulation & selection methods.
* Mostly used no standard based NoSQL query language.
* Text-based protocols mostly used with HTTP REST with JSON.<br>
## Types of NoSQL Database 
Types of NoSQL databases and the name of the databases system that falls in that category are:<br>

  * Column-oriented Graph : Table Casandra.
  * Key value store: Memcached, Redis, Coherence
  * Tabular: Hbase, Big Table, Accumulo
  * Document based: MongoDB, CouchDB, Cloudant
 ## Key Value store
 
 In key value store NoSQL data is stored in key/value pairs. It is designed in such a way to handle lots of data and heavy load.Key-value pair storage databases store data as a hash table where each key is unique, and the value can be a JSON, BLOB(Binary Large Objects), string, etc.<br>

![Key Value Store](https://upload.wikimedia.org/wikipedia/commons/5/5b/KeyValue.PNG)<br>

Some of the example of Key Value Store NoSQL are Redis, Coherence<br>
**Advantages of key value store database**
* NoSQL database is used as a collection, dictionaries, associative arrays.
* Store schema-less data.
* Work best for shopping cart contents.
## Column-oriented Graph
Column-oriented databases work on columns. Every column is treated separately. Values of single column databases are stored contiguously.<br>
**Advantagges of columnn-oriented graph databases
* High performance aggregation.
* Efficient for data warehouses.
* One column family can have vaiable number of columns
* Ver sparse, most value have null value
* Some examples are casandra.<br>
![Column-oriented Graph](https://www.guru99.com/images/1/101818_0537_NoSQLTutori7.png)
## Graph based database

A graph type database stores entities as well the relations amongst those entities. The entity is stored as a node with the relationship as edges. An edge gives a relationship between nodes. Every node and edge has a unique identifier.<br>
**Advantages of Graph based database**
* Focus on modelling of the data.
* Scale to the complexity of the data.
* Interface query langugage.
* Based on Graph theory.
* Basically used for social sites.
* Some examples are FlockDB.<br>
![Graph based database](https://dist.neo4j.com/wp-content/uploads/20180711200201/twitter-users-graph-database-model-peter-emil-johan.png?_gl=1*11b4k5u*_ga*MTEyNTkyNTUwNy4xNjQ0NDA3NzI1*_ga_DL38Q8KGQC*MTY0NDQwNzcyNC4xLjAuMTY0NDQwNzcyNC4w&_ga=2.20634488.1517951860.1644407729-1125925507.1644407725)
## Document-Oriented database

Document-Oriented NoSQL DB stores and retrieves data as a key value pair but the value part is stored as a document. The document is stored in JSON or XML formats. The value is understood by the DB and can be queried.The document type is mostly used for CMS systems, blogging platforms, real-time analytics & e-commerce applications. It should not use for complex transactions which require multiple operations or queries against varying aggregate structures.Some examples are MongoDB
<br>
**Working of Document-Oriented database**
![Document-Oriented database](data:image/png;base64,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
