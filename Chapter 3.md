# Questions

1.- Why is a natural key not needed in the data model?
A = Because the data is intended to be consumed en masse.

2.- What increases the storage costs in the key / value store?
A = It indexes your data and provides unnecessary services

3.- What is the difference between a file system and a key / value store?
A = A file system gives you exactly what you need and nothing else, while not limiting your ability to adjust the cost of storage against the cost of processing.

4.- What is the difference between distributed file systems and normal file systems?
A = The operations you can perform with a distributed file system are usually more limited than with a normal file system.

6.- Advantages of vertical partitioning
R = Make the batch layer more efficient. While it's not strictly necessary for the batch layer, as the batch layer is capable of looking at all the data at once and filtering out what it doesn't need, vertical partitioning enables large performance gains, so it's important to know how to use the technique.

7.- Which scheme provides a natural vertical partition of the data?
R = The graphic scheme
