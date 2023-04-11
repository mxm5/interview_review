learn how to run a java program using main method

# Creating main method

	The text is about creating a main() method in Java, which is necessary for the JVM to call the code in a program. The main() method is the entry point for the program, and it must be present in a class with the correct signature and access modifiers. The text provides an example of a simple main() method and explains the meaning of each part of the signature, including the access modifier, static keyword, void return type, and parameter list. The text also covers the rules for naming the file and the class, and the importance of using the correct extension for the file. Additionally, the text mentions optional modifiers that can be used with the main() method, such as the final keyword. Overall, the text provides an introduction to the main() method in Java and its importance in running a program.

# passing parameters to main program

	-   Explanation of how to send data to a program's main() method in Java.
	-   Modifying the Zoo program to print out the first two arguments passed in.
	-   Using args[0] to access the first element of an array in Java.
	-   Running the program using javac and java commands.
	-   Handling arguments with spaces by using quotes.
	-   What happens when not enough arguments are passed in.
	-   The JDK contains a compiler and Java class files run on the JVM.
	-   A shortcut for launching single-file source-code programs in Java.

```shell
java Zoo.java Bronx Zoo
```

```shell
javac Zoo.java 
java Zoo "San Diego" Zoo
```

```shell
java Zoo.java Bronx Zoo
```