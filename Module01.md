# az-dp-900

## module 1
Identify data formats
+ structured 
+ semi-structred
+ unstructured

#### Broad categories of data store
+ File Stores
+ Databases

#### File Storage
+ delimited text files
  + csv, tsv, fixed width 
+ Javascript Object Notation(JSON)
+ Extensible Markup Language(XML)
+ Binary Large Object(BLOB)
+ Optimized file formats
  + AVRO - row based, header json, Apache 
  + ORC - Optimized Row Columnar, stores in columns
  + Parquet - Columnar

#### Databases
+ Relational db
+ Non-relational db aka NoSQL
  + Key-value db
  + Document db (specific of key-value where value is of JSON -f)
  + Column family db
    + ex like column A Customer is actually a.1 and a.2, where a.1 is customer name & a.2 is customer address.
    + Rows can consists of mutiple grouped column family like A
  + Graph db (sigh, full of connected nodes ig)

### Transactional Data Processing
 + ex like banking, high volume, discrete
 + OLTP -Work performed by these txnl systems
  + ACID semantics
   + Atomicity (payment pass/fail)
   + Consistency (one valid state 2 another, fund sent match in the target acc)
   + Isolation ( ex post payment, balance retireved should be consistent)
   + Durability (Commmiting the txn)   

### Analytical Data Processing

### Roles in Organizations
+ Database Administator (Design, Implement, Maintain, Securing etc..)
+ Data Engineer (ETL, data ingestion Xfrm, monitor, maintaining privacy)
+ Data Analyst (identifying trends, relationships in Data, Design and Building New models, Report generation)

### Identify Data Services
+ Az SQL (Az Family of SQL)
 +  Az SQL
 +  Az SQL Managed Instance
 +  Az SQL for VM
+ Azure SQL for open source data base systems
  + Az SQL for MySQL
  + Az SQL for MariaDB
  + Az SQL for Postgres
  + Az SQL Edge (IOT)
+ Az Blob Storage (Blob, table , fileshares)
+ Az Data Factory
+ Az DataBricks
+ Az HDInsight
+ Az Cosmos DB
+ Az Synapse Analytics
+ Az Stream Analytics
+ Az Data Explorer
+ Microsoft Purview
+ Mircrosoft Fabric ((ETL, SaaS soln for Data Analytics)



