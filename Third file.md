# Questions

1.- What kind of errors are the ones that take the longest to solve?
  R= those of corruption

2.-Why are data corruption problems difficult to solve?
  R= Because it has very little context on how the corruption occurred

3.- Advantages of the enforceable schema
  R= Get errors when writing data, giving you full context on how and why the data became invalid. Also, the error prevents the program from corrupting the master data set by writing that data

4.- What fields make up Thrift's workhorses?
  R= ■ Primitive data types (strings, integers, longs, and doubles)
     ■ Collections of other types (lists, maps and sets)
     ■ Other structures and unions

5.- What do you do the unions?
  R= Allow schema to evolve as data evolve

6.- How are the edges represented?
  R= As a 2 node structure

7.- Why is it crucial that the schemes can evolve over time?
  R= Because as your business requirements change, you will need to add new data types

8.- What are the rules that must be followed to change a scheme but that the data is still compatible?
  R= ■ The fields can be renamed.
     ■ You can delete a field, but you should never reuse that field ID.
