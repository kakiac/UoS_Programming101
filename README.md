## Introduction to Programming (2021-22, University of Suffolk)

<img src="https://icanbea.org.uk/media/shapes/original/x-large/5000/5100/university-of-suffolk-logo.png" height="100" >

### Module info 

| Module Title  | Introduction to Programming |
| ------------  | -------------               |
| Module Code   | IFDCTS106                   |
| Level         | 4 (1st year undergraduate)  |
| School        | School of EAST              |
| Github Repo   | UoS_Programming101          |

This module will introduce the concepts of programming and a modern programming language. Although it is likely that the majority of students will have some programming experience, none will be assumed. Structured programming constructs, procedural programming and object-oriented programming will be covered. Elements of agile development will be covered. 

The aims of the module are: 

 * to introduce the concept of a computer program, programming languages and program production methods; 
 * to introduce generic high-level programming language concepts; 
 * to introduce the concepts and structures of structured programming; 
 * to introduce the concepts of object-oriented development and programming; 
 * to introduce the concepts of Agile Development. 

### Module outline


| Session       | Topic                       | Resources         | Student Tasks   |  Date             |
| ------------  | -------------               |------------------ | --------------  |  --------------   |
| Lecture 1     | Getting Started: Computers, Programming and Java  
| Lecture 2     | Java Concepts I: Basic Operators & Variables
| Lecture 3     | Java concepts II: String Operators & Other data types
| Lecture 4     | Java in context: High and low level languages, Programming language paradigms
| Lecture 5     | What if? Java Conditionals
| Lecture 6     | Java Loops 
| Lecture 7     | Java Methods
| Lecture 8     | Java Objects & Classes 
| Lecture 9     | Errors & Exceptions
| Lecture 10    | Inheritance (subclasses & superclasses)
| Lecture 11    | Working with Files in Java
| Lecture 12    | Programming in Java: where next?


#### Lecture 1: Getting Started: Computers, Programming and Java
<details>
  <summary>Content Outline</summary>

 * Welcome
 * Why Study Programming?
 * Programming Languages
 * Why Java?
 * What Is Object-Oriented Programming?
 * 'Hello World' java program: structure
 * Using the command line to compile and run Java
 * Using the Eclipse IDE to edit, compile and run Java
 * Editing a Java program (including tools such as: colour coding, autofilling, saving/exporting eclipse project, workspace)
 * Compiling a Java Program
 * Running a Java program
 * Your turn: 
    * install Java & Eclipse
    * run the 'Hello World' program

 </details>
 
#### Lecture 2: Java Concepts I: Basic Data Types (string, int) & Variables
<details>
  <summary>Content Outline</summary>
 
 * recap of last lecture
 * 'Good morning World': String Data Type
 * What is a Variable?
 * Declaring Variables
 * Assigning Variables (incl. memory diagrams)
 * Printing Variables
 * Java Basic Data Types: int 
 * Integers and Basic Operators (+,-,*,/)
 * Working with integers and variables (declaring, assigning, printing)
 * Comments
 * Help! There is an error (a first look at understanding compiler error messages e.g very simple function spelling message or closing ; at end of line)
 * Your turn: 
    * change 'Hello world' to 'good morning world'
    * Running lecture2-1.java; replace numbers with a variable
    * Correcting the mistakes in lecture2-2.java & sucessfully running it

   </details>
   
#### Lecture 3: Java Concepts II: More Data types & Operators
<details>
  <summary>Content Outline</summary>
   
* recap of last lecture
* String concatenation
* Other Numerical Data types (double, float, date)
* Other Java Data Types (boolean, char)
* Assignment Operators (= vs ==)
* Java Comparison operators ( ==, !=, >, <, >=, <=)
* Final Variables
* Your turn:
   * Exercise 3-1: The point of this exercise is (1) to use string concatenation to display values with different types (int and String), and (2) to practice developing programs gradually by adding a few statements at a time.

      1. Create a new program named Date.java. Copy or type in something like the Hello World program and make sure you can compile and run it.
      2. Following the example in Section 2.4, write a program that creates variables named day, date, month, and year. The variable day will contain the day of the week (like Friday), and date will contain the day of the month (like the 13th). Assign values to those variables that represent today’s date.
      3. Display the value of each variable on a line by itself. This is an intermediate step that is useful for checking that everything is working so far. Compile and run your program before moving on.
      4. Modify the program so that it displays the date in standard American format; for example: Thursday, July 18, 2019.
      5. Modify the program so it also displays the date in European format. The final output should be as follows:

```
American format: Thursday, July 18, 2019
European format: Thursday 18 July 2019
```
   
   * Exercise 3-2: The point of this exercise is to (1) use some of the arithmetic operators, and (2) start thinking about compound entities (like time of day) that are represented with multiple values.

      1. Create a new program called Time.java. From now on, we won’t remind you to start with a small, working program, but you should.
      2. Following the example program in Section 2.4, create variables named hour, minute, and second. Assign values that are roughly the current time. Use a 24-hour clock so that at 2:00 PM the value of hour is 14.
      3. Make the program calculate and display the number of seconds since midnight.
      4. Calculate and display the number of seconds remaining in the day.
      5. Calculate and display the percentage of the day that has passed. You might run into problems when computing percentages with integers, so consider using floating-point.
      6. Change the values of hour, minute, and second to reflect the current time. Then write code to compute the elapsed time since you started working on this exercise.

Hint: You might want to use additional variables to hold values during the computation. Variables that are used in a computation but never displayed are sometimes called “intermediate” or “temporary” variables.

</details>

#### Lecture 4: Java in context: Programming language paradigms
<details>
  <summary>Content Outline</summary>

 * recap of last lecture
 * Programming language paradigms: 
  * imperative (procedural, object oriented)
  * declarative (functional, logic, mathematical, reactive) 
  * multiparadigm languages
 * Introduction to low vs high level languages 
 * Example of 'hello world' program in different programming language paradigms
 * Java: an Object Oriented Programming language

</details>

#### Lecture 5: What if? Java Conditionals
<details>
  <summary>Content Outline</summary>

 * Conditional statements in programming
 * Java Conditions and if statements
   * logical conditions from maths (Java Comparison operators ( ==, !=, >, <, >=, <=)) - refresher
   * conditional statements: if, else, else if
 * Conditionals: switch statements; 'break' keyword
 
</details>

#### Lecture 6: Java Loops 

<details>
  <summary>Content Outline</summary>

* understanding loops 
* Java 'while' loop
* do - while loop
* 'For' loop
* 'for-each' loop
* break & continue
* Java Lambda expressions (parameter -> expression)

   </details>

#### Lecture 7: Java Methods

<details>
  <summary>Content Outline</summary>

* back to hello world program - Java program anatomy
* Method = Function
* create a method
* call a method
* method parameters
* method arguments (incl. multiple parameters)
* return values
* Bringing it all together: a conditional inside a method 
* Method overloading
* Method Scope
* A method calling itself: recursion
 
   </details>

#### Lecture 8: Java Objects & Classes 

<details>
  <summary>Content Outline</summary>
   
* refresher: Programming language paradigms - Object Oriented Programming
* Programming using Templates: Java Objects and classes:
   * refresher: Java is an object oriented language
   * What is a Java object?
   * what is a Java class?
   * creating a class
   * creating an object
   * Working with multiple objects & classes
   * Class attributes (accessing, modifying, defining multiple attributes)
   * Class access modifiers (public vs static methods, private, abstract, default, protected) [encapsulation?] 
   * Better together: methods within classes
   * Java special classes I : constructors (defining, parameters)
   * Java special classes II: Scanner (user input)
   * Java special classes III: Date & time (java.time)
   * Java special classes IV: wrapper classes (https://www.w3schools.com/java/java_wrapper_classes.asp)
   * Importing a class from a package
   * nesting classes (inner classes)
   
   </details>

#### Lecture 9: Errors & Exceptions
<details>
  <summary>Content Outline</summary>
   
Content:
* compiler errrors
* Runtime errors
* Other errors
* 'try' and 'catch' statements
* 'finally' and 'throw' statements
*  Your turn:
      * Play 'Stump the Chump': Start with a program that compiles and runs correctly. One player looks away, while the other player adds an error to the program. Then the first player tries to find and fix the error. You get two points if you find the error without compiling the program, one point if you find it using the compiler, and your opponent gets a point if you don’t find it. 

   </details>

#### Lecture 10: Inheritance (subclasses & superclasses)
<details>
  <summary>Content Outline</summary>
   
* the concept of inheritance in java
* why inherit?
* why bother reusing your code?
* subclasses vs superclasses
* Extending classes (https://www.w3schools.com/java/java_polymorphism.asp)

   </detail>

#### Lecture 11: Working with Files in Java

Content:
 * reading a file (File class, java.io package)
 * testing if file is readable - canRead()
 * testing if file is writable - canWrite()
 * create an empty file - createNewFile()
 * delete a file - delete()
 * test if file exists - exists()
 * return name of the file - getName()
 * return absolute pathname of file - getAbsolutePath()
 * return size of file in bytes - length()
 * create a directory - mkdir()
 * write to a file

#### Lecture 12: Programming in Java: where next? [in progress. I am still thinking about what to include here]
 * recap of whole module: where we started, what we have achieved - our 'hello world' program!
 * Basic GUI design and implementation 
 * Basic networking 
 * Basic thread-based programming 
 * Agile Development concepts 
 * Test-driven development 
 * Pair programming 
 * Refactoring  
 * Useful resources:
   * Java reserved keywords: https://www.w3schools.com/java/java_ref_keywords.asp
   * Java string methods: https://www.w3schools.com/java/java_ref_string.asp
   * Java math methods: https://www.w3schools.com/java/java_ref_math.asp
   * Java exercises: https://www.w3schools.com/java/java_exercises.asp
