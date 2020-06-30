# Questions
1- What is a log?
  R= Is an append-only data file

2.- Advantages of append-only logs.
  R=
- Appending and segment merging are sequential write operations, which are generally much faster than random writes, especially on magnetic spinning-disk hard drives. To some extent sequential writes are also preferable on flash-based solid state drives (SSDs).
  
- Concurrency and crash recovery are much simpler if segment files are appendonly or immutable. For example, you don’t have to worry about the case where a crash happened while a value was being overwritten, leaving you with a file containing part of the old and part of the new value spliced together.
  
- Merging old segments avoids the problem of data files getting fragmented over time.
  
3.- What is a data warehouse?
R=  is a separate database that analysts can query to their hearts’ content, without affecting OLTP operations

4.- What is a hash table?
  R= A Hash Table is a data structure which stores data in an associative manner. In a hash table, data is stored in an array format, where each data cell has its own unique index value. Access of data becomes very fast if we know the index of the desired data.
  
5.- Why Cassandra and HBase are not columns oriented?
  R= within each column family, they store all columns from a row together, along with a row key, and they do not use column compression

6.- Why the data model of a data warehouse is most commonly relational?
  R= Because SQL is generally a good fit for analytic queries
  
7.- How the book refers to Transaction processing?
R= just means allowing clients to make low-latency reads and writes as opposed to batch processing jobs, which only run periodically
