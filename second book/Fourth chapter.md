# Questions
1.- What are the forms of data representation given in the book?
  R=
- In memory, data is kept in objects, structs, lists, arrays, hash tables, trees, and so
on. These data structures are optimized for efficient access and manipulation by
the CPU (typically using pointers).

- When you want to write data to a file or send it over the network, you have to
encode it as some kind of self-contained sequence of bytes (for example, a JSON
document). Since a pointer wouldn’t make sense to any other process, this

 2.- What is serizalization?
  R= The translation from the in-memory representation to a byte sequence

 3.- What are Thrift and Protocol Buffers?
  R=  binary encoding libraries that are based on the same principle
  
 4.- What is the risk of changing the datatype of a field?
  R= Tthat values will lose precision or get truncated
  
 5.- What is the schema evolution?
  R= It is the concept that refers to the fact that the schemas, with the passage of time, change
  
 6.- What is Avro?
  R= 
