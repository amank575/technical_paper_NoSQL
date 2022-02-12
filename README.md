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
Types of NoSQL databases and the name of the databases system that falls in that category are:

  * Column-oriented Graph : Table Casandra.
  * Key value store: Memcached, Redis, Coherence
  * Tabular: Hbase, Big Table, Accumulo
  * Document based: MongoDB, CouchDB, Cloudant
  
 ## Key Value store
 
 In key value store NoSQL data is stored in key/value pairs. It is designed in such a way to handle lots of data and heavy load.Key-value pair storage databases store data as a hash table where each key is unique, and the value can be a JSON, BLOB(Binary Large Objects), string, etc.
<br></br>
**Advantages of key value store database**
* NoSQL database is used as a collection, dictionaries, associative arrays.
* Store schema-less data.
* Work best for shopping cart contents.
<br></br>
 <span style="display:block;text-align:center">![Key Value Store](https://upload.wikimedia.org/wikipedia/commons/5/5b/KeyValue.PNG)</span>
## Column-oriented Graph
Column-oriented databases work on columns. Every column is treated separately. Values of single column databases are stored contiguously.
<br></br>
**Advantagges of columnn-oriented graph databases**
* High performance aggregation.
* Efficient for data warehouses.
* One column family can have vaiable number of columns
* Ver sparse, most value have null value
* Some examples are casandra.<br></br>
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
![Graph based database](https://database.guide/wp-content/uploads/2016/06/graph_database_relationship_example.png)<br>
## Document-Oriented database

Document-Oriented NoSQL DB stores and retrieves data as a key value pair but the value part is stored as a document. The document is stored in JSON or XML formats. The value is understood by the DB and can be queried.The document type is mostly used for CMS systems, blogging platforms, real-time analytics & e-commerce applications. It should not use for complex transactions which require multiple operations or queries against varying aggregate structures.Some examples are MongoDB
<br>
**Document-Oriented database and RDBMS**
<br></br>
![Document-Oriented database](https://phoenixnap.com/kb/wp-content/uploads/2021/05/document-database-illustration.png)<br>
## Reference
https://www.geeksforgeeks.org/introduction-to-nosql/<br>
https://www.mongodb.com/nosql-explained<br>
https://www.guru99.com/nosql-tutorial<br>
https://database.guide/wp-content/uploads/2016/06/graph_database_relationship_example


