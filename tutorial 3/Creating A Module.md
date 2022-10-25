Basics about go functions:
- In Go, a function whose name starts with a capital letter can be called by a function not in the same package
    - This is known in Go as an exported name

Basics about operators:
- In Go, the := operator is a shortcut for declaring and initializing a variable in one line.
    -  This is similar to stored functions in postgres for assigning a value to a variable

Referencing local packages:
- To reference a module locally you have to modify the reference. This is done by the following:
```
go mod edit -replace example.com/greetings=../greetings
```
