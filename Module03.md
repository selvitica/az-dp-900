# az-dp-900

## Module 3
Data Analytics
1. Data Ingestion and Processing (ETL,ELT)
2. Analytical Data Store (datawarehouse, datalakes etc)
3. Analytical Data Model (cubes)
4. Data Visualization (dasboards, bi -reports, kpi's etc)

#### Data Ingestion Pipelines
+ DDL (Data Definition Language) *CREATE, ALTER, DROP, RENAME*
+ DCL (Data Control Language) *GRANT, DENY, REVOKE*
+ DML (Data Manipulation Language) *SELECT, INSERT, UPDATE, DELETE*

#### Non-Relational Data
+ Az Blob Storage (page, block, append) (hot,cool,archive)
+ Az DataLake Storage (Hierarchical Namespace)
+ Az Files
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

### Identify Azure Cosmos DB APIs
+ Azure Cosmos DB for NoSQL (non-rel, store and query JSON documents)
+ Azure Cosmos DB for MongoDB (Binary JSON)
+ Azure Cosmos DB for PostgreSQL (relational)
+ Azure Cosmos DB for Table
+ Azure Cosmos DB for Apache Cassandra
+ Azure Cosmos DB for Apache Gremlin (data in which entities and their relationships to one another are represented in a graph using vertices and edges)


