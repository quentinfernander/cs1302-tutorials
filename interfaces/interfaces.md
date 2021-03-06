__IN PROGRESS; THIS TUTORIAL IS NOT YET FINISHED.__

# Interfaces

TODO write intro

**NOTE:** Many of the code examples in this tutorial are adapted from
[[1]](https://www.pearson.com/us/higher-education/program/Lewis-Java-Foundations-Introduction-to-Program-Design-and-Data-Structures-4th-Edition/PGM76634.html)
under academic fair use.

### Prerequisites

This tutorial assumes that the reader has a knowledge of basic Unix commands and experience working 
with a command-line text editor (e.g. emacs, vi, etc.). To get the most out of this tutorial, 
you should follow along and take notes.

### Getting Started

The steps in this tutorial assume that you are logged into the Nike server. 

1. Use the following command to download and execute a shell script that retrieves 
   the starter code for this tutorial and places it into a subdirectory 
   called `cs1302-interfaces`:

   ```
   $ curl -s -L https://git.io/fhgce | bash
   ```
  
1. Change into the `cs1302-interfaces` directory that was just created and look around. There should be
   multiple Java files contained within the directory structure. To see a listing of all of the 
   files under the current directory, use the `find` command as follows:
   
   ```
   $ find .
   ```
   
   Inspect each `.java` file that was listed. You will notice that some of them contain interfaces
   instead of classes. They can be identified by looking for the `interface` keyword instead of
   the `class` keyword in the overall type declaration specified near the top of the file. We say
   "type" declaration because a `.java` file can be used to declare any kind of reference type in
   Java, including classes, interfaces, and class-based enumerations. A **reference type** in Java
   is any type that can serve as the type for a variable that refers to an object. Such a variable
   is known as a **reference variable**. We will elaborate on this terminology a little more later 
   in this tutorial.

### What is an Interface?

In its simplest form, a Java **interface** is a reference type composed of abstract methods and 
constants. An **abstract method** is a non-static method without an implementation. Constants
are variables (static or not) that are declared using the `final` keyword. As of Java 8, the
technical definition for an *interface* allows it to contain only the following:
abstract methods, constants, static methods, nested types, and default methods 
[[2]](https://docs.oracle.com/javase/tutorial/java/IandI/createinterface.html).
Nested types and default methods will not be covered in this tutorial. 

Interfaces are used to specify that a type *can do* a set of things specified by its
abstract methods and constants. An interface serves as a contract for the classes that 
claim to implement the interface. Multiple classes can implement the same interface,
each providing their own implementation of the contracted functionality. For this
reason, it is important that the documentation for an interface describe *what* a method
does and necessarily *how* it should do it. Such documentation is usually written using
Javadoc comments in the interface.

1. 

1. 

### Implementing an Interface

TODO write intro

1.

1.

### References

* [[1] Lewis, DePasquale, and Chase. _Java Foundations_. Fourth Edition.](https://www.pearson.com/us/higher-education/program/Lewis-Java-Foundations-Introduction-to-Program-Design-and-Data-Structures-4th-Edition/PGM76634.html)
* [[2] Oracle Java Tutorials: Interfaces](https://docs.oracle.com/javase/tutorial/java/IandI/createinterface.html)


<hr/>

[![License: CC BY-NC-ND 4.0](https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg)](http://creativecommons.org/licenses/by-nc-nd/4.0/)

<small>
Copyright &copy; Michael E. Cotterell, Brad Barnes, and the University of Georgia.
This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a> to students and the public.
The content and opinions expressed on this Web page do not necessarily reflect the views of nor are they endorsed by the University of Georgia or the University System of Georgia.
</small>
