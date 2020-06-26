# Questions
1.- Advantages of append-only logs
  R= Appending and segment merging are sequential write operations, which are generally much faster than random writes, especially on magnetic spinning-disk hard drives.
  To some extent sequential writes are also preferable on flash-based solid state drives (SSDs).
  
  Concurrency and crash recovery are much simpler if segment files are appendonly or immutable. For example, you don’t have to worry about the case where a crash happened
  while a value was being overwritten, leaving you with a file containing part of the old and part of the new value spliced together.
  
  Merging old segments avoids the problem of data files getting fragmented over time.
  
  2.- 
