classes are building blocks
use most class - create obj = runtime instance of class
objects = state
ref vars point obj

# Feilds methods
	The text discusses the primary elements of Java classes, which are methods and fields (variables). It explains that variables hold the state of the program, and methods operate on that state. The programmer's job is to arrange these elements in a useful way. The text then presents an example of a simple Java class, Animal, and explains the use of keywords like public and class. It then adds a field (variable) named name and two methods, getName() and setName(), with explanations of their return types and parameters. Finally, the text asks the reader to identify the method signature of a given example method, which is numberVisitors(int).

variables hold the state
methods operate on that state
example

# Comments
	The text explains the use of comments in Java programming and how they can make code easier to read. There are three types of comments: single-line comments, multiple-line comments, and Javadoc comments. Single-line comments begin with two slashes and are ignored by the compiler until the end of the line. Multiple-line comments begin with /* and end with _/ and can span multiple lines. Javadoc comments begin with /_* and are used for documenting code. The text also provides an exercise to identify different types of comments and their structure.

single-line comments,
```
//
```
multiple-line comments,
```
/* */
```
and Javadoc comments
```
/** */
```
# 	Classes and Source Files
	The text discusses classes and source files in Java. It explains that each Java class is defined in its own .java file and that a top-level type is a data structure that can be defined independently within a source file. The text also explains that a top-level class is often public, but Java does not require it to be so. The text notes that it is possible to put two types in the same file and that only one of them can be public. Additionally, the text explains that if there is a public type, it needs to match the filename. Finally, the text mentions that this chapter includes numerous references to topics that are discussed in more detail in later chapters, and that the examples and rules in this chapter are kept simple.

top-level class is often public 
2 class can be in 1 file one public
public type, it needs to match the filename