
# Database in C++

This project is a database management system, which takes commands from the command line.
This project aims to replicate a full-fledged database management system. I have created this project to implement my learnings from the 
course [DA214: Database Management Systems] and 
[DA215: Database Management Systems Lab]. 

First off, I started by creating a [REPL](https://en.wikipedia.org/wiki/Read%E2%80%93eval%E2%80%93print_loop) for the command line interface.
Then, I worked on the internal architecture of storing the data. The architecture was first based on rows, which formed into pages arranged
in an array, then defined a primitive cache architecture for the same. Later, the data structure used for storing pages was changed to a 
`B+ tree`. Next, I worked on saving the tree in a file, so that the database is saved after exiting the command line. Lastly, I worked on 
introducing two functionalities to the database, namely `select` and `insert`.

# Features

1. Stores all the data in the form of `rows`, which in turn is stored in the form of `pages` which in turn is stored in the form of a `B+ tree`
2. Insertion of an entry
3. Selection of all the entries in the database


# Credits

This project was made by [Prakhar Punj](https://github.com/Guardian-Angel1)