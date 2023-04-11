	1.  Java has thousands of built-in classes and countless more from developers, and it needs a way to organize them.
	2.Java organizes classes into packages, which are logical groupings for classes.
	3.  Import statements tell Java which packages to look in for classes.
	4. The absence of an import statement can cause a compilation error.
	5. static import that allows you to use variables and method names without having to keep specifying the class name,

thousands of built-in classes packages organize them
package = logical grouping
package need import tell compiler find
static imports = no class call
# packages

	The text explains how Java classes are organized into packages and how the import statement is used to tell the compiler where to find a class. It compares this to how mailing a letter works, where the address is like the package name in Java and the apartment number is like the class name. The text also discusses how package names are hierarchical and may include the name of the website they came from. It notes that package names should consist of mostly letters or numbers separated by periods, and that the exam may try to trick you with invalid variable names but not invalid package names. The text also mentions that it will cover imports with wildcards, naming conflicts with imports, how to create a package, and how the exam formats code in later sections.
	-   Java classes are grouped into packages.
	-   The import statement tells the compiler which package to look in to find a class.
	-   Package names are hierarchical, starting with a top-level identifier like "java", and can include more specific child packages.
	-   Package names follow a naming convention of mostly letters or numbers separated by periods, with a couple of other characters allowed.
	-   The exam may try to trick you with invalid variable names, but not with invalid package names.
	-   The text also covers topics such as imports with wildcards, naming conflicts with imports, creating a package of your own, and how the exam formats code.

packages hierarchical
naming letters
reverse website name

# Wildcards
	This text explains how to use wildcards to import multiple classes from the same package in Java. The asterisk (*) in the import statement is a wildcard that matches all classes in the package. The import statement only imports classes directly under the package, not child packages, fields, or methods. The compiler only includes what's necessary, so including many classes does not slow down program execution. The choice of approach is personal preference, and both approaches may appear on the exam.
	

`*` imports multiple class in pkg
 imports classes directly under the package, not child , fields, methods

