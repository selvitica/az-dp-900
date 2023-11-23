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
