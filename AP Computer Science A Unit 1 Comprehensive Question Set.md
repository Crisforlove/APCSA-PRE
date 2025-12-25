### Topic 1.6 — Compound Assignment Operators

#### 1
Consider the following code segment.
```java
int x \= 7;
int y \= 3;
x \+= y;
y \*= 2;
x %= y;
```
What is the value of x after the code segment has been executed?
A) 1
B) 4
C) 10
D) 6
E) 0  
**
**Answer:** B

#### 2
```java
Which of the following is equivalent to the statement x \= x \+ 1;?I. x++;II. x \+= 1;III. \++x; (Note: While valid Java, CED focuses on post-increment)
```
A) I only
B) II only
C) I and II only
D) II and III only
E) I, II, and III  
**
**Answer:** E

#### 3
Consider the following code segment.
```java
int result \= 20;
result /= 4;
result \+= 2;
result \*= 3;
```
What is the value of result?
A) 15
B) 21
C) 11
D) 7
E) 18  
**
**Answer:** B

#### 4
Consider the following code segment.
```java
int k \= 10;
k++;
k--;
k \+= 5;
k \-= 2;
```
What is the final value of k?
A) 10
B) 15
C) 13
D) 12
E) 14  
**
**Answer:** C

#### 5
```java
A programmer wants to double the value of a variable score. Which of the following statements will accomplish this?I. score \= score \* 2;II. score \*= 2;III. score \+= score;
```
A) I only
B) II only
C) I and II only
D) II and III only
E) I, II, and III  
**
**Answer:** E

#### 6
What is the value of n after the following code executes?
```java
int n \= 15;
n %= 4;
n \+= n;
```
A) 3
B) 6
C) 7
D) 1
E) 2  
**
**Answer:** B

#### 7
Consider the following code segment.
```java
int a \= 5;
int b \= 2;
a \*= b \+ 3;
```
What is the value of a?
A) 13
B) 25
C) 10
D) 15
E) 11  
**
**Answer:** B

#### 8
Which compound assignment operator is used to find the remainder and assign it to the variable?
A) rem=
B) %=
C) /=
D) ^=
E) &=  
**
**Answer:** B

#### 9
Consider the following code segment.
```java
int count \= 0;
count++;
count++;
count--;
```
What is the value of count?
A) 0
B) 1
C) 2
D) \-1
E) 3  
**
**Answer:** B

#### 10
Which of the following statements about compound assignment operators is true?
A) They can only be used with int variables.
B) They perform an operation and an assignment in one step.
C) x \+= 1 is slower than x \= x \+ 1.
D) They cannot be used with double variables.
E) They are ignored by the compiler.  
**
**Answer:** B

### Topic 1.7 — Application Program Interface (API) and Libraries

#### 1
Which of the following best describes an **Application Programming Interface (API)**?
A) A physical device used to connect computers.
B) A library of code that allows different software programs to communicate.
C) A collection of rules for writing syntax errors.
D) A tool used only for designing hardware.
E) A documentation that explains how to use classes and methods in a library.  
**
**Answer:** E

#### 2
In Java, which of the following is used to group related classes together?
A) A method
B) A variable
C) A package
D) A loop
E) An expression  
**
**Answer:** C

#### 3
A programmer needs to use a class that is not in the java.lang package. What must they do to access it?
A) Write the entire code of the class manually.
B) Use an import statement at the beginning of the program.
C) Reinstall the Java Development Kit.
D) Change the variable types to double.
E) Nothing, all classes are available by default.  
**
**Answer:** B

#### 4
Which of the following refers to the **data** related to a class?
A) Behaviors
B) Methods
C) Attributes) Signatures
E) Packages  
**
**Answer:** C

#### 5
Which of the following refers to what an **instance** of a class can do?
A) Attributes
B) Variables
C) Behaviors
D) Declarations
E) Literals  
**
**Answer:** C

#### 6
The java.lang package in Java:
A) Must be imported manually.
B) Is only used for mathematical calculations.
C) Is available by default in every Java program.
D) Contains only the Scanner class.
E) Is used to read text files.  
**
**Answer:** C

#### 7
Where can a programmer find information about the methods, parameters, and return types of a provided class?
A) In the computer's processor.
B) In the API documentation.
C) Inside a while loop.
D) By checking for syntax errors.
E) Only by reading the original source code of the library.  
**
**Answer:** B

#### 8
Which of the following is a collection of classes?
A) A variable
B) A library
C) A method signature
D) A primitive type
E) A literal  
**
**Answer:** B

#### 9
Attributes are typically stored in:
A) Methods
B) Loops
C) Variables
D) Packages
E) Comments  
**
**Answer:** C

#### 10
Which of the following is true about utilizing existing classes?
A) It makes programming more difficult and error-prone.
B) It allows programmers to use pre-written and tested code.
C) It is only possible in the main method.
D) It requires permission from the College Board for every use.
E) It is not allowed in the AP Java subset.  
**
**Answer:** B

### Topic 1.8 — Documentation with Comments

#### 1
What is the primary purpose of writing **comments** in a program?
A) To make the program run faster.) To inform the compiler of special rules.
C) To help human programmers understand the code.
D) To prevent runtime exceptions.
E) To declare variables.  
**
**Answer:** C

#### 2
Which of the following is a **precondition** for a method?
A) A condition that must be true after the method executes.
B) A statement that returns a value to the caller.
C) A condition that must be true before the method is called for it to work correctly.
D) A type of syntax error found by the compiler.
E) A comment that describes the author of the code.  
**
**Answer:** C

#### 3
Which of the following is a **postcondition** for a method?
A) A condition that describes the outcome or return value after the method executes.
B) A condition that must be true before the method starts.
C) A comment used to hide code from the compiler.
D) A rule that prevents the method from being overloaded.
E) The first line of a method's implementation.  
**
**Answer:** A

#### 4
Which symbol is used for a **single-line comment** in Java?
A) /\*
B) //
C) /\*\*
D) \\\\
E) \--  
**
**Answer:** B

#### 5
What happens to comments when a Java program is compiled?
A) They are converted into machine code.
B) They are checked for syntax errors.
C) They are ignored by the compiler.
D) They are sent to the API documentation server.
E) They cause the program to pause during execution.  
**
**Answer:** C

#### 6
Which type of comment is specifically used to create **Javadoc** documentation?
A) // comment
B) /\* comment \*/
C) /\*\* comment \*/
D) \-- comment
E) \# comment  
**
**Answer:** C

#### 7
If a method’s precondition is not met:
A) The compiler will always report a syntax error.
B) The method is not guaranteed to behave as expected.
C) The program will automatically fix the inputs.
D) The postcondition will always be true.
E) The method will skip its execution and return 0\.  
**
**Answer:** B

#### 8
A programmer writes a method to calculate a square root. The comment says // Precondition: x \>= 0\. What does this mean?
A) The method will return a negative number if x is negative.
B) The caller should ensure x is non-negative before calling the method.
C) The method will automatically convert negative numbers to positive.
D) The compiler will block any calls with negative numbers.
E) The method is only used for integers.  
**
**Answer:** B

#### 9
Postconditions typically describe:
A) The initial state of the parameters.
B) The current value of an object's attributes after execution.
C) The version of the compiler being used.
D) The time it took for the program to run.
E) The number of comments in the file.  
**
**Answer:** B

#### 10
Which of the following is a **multi-line (block) comment**?
A) // This is a comment
B) /\* This is a comment \*/
C) \\ This is a comment \\
D) COMMENT: This is a comment
E) \[This is a comment\]  
**
**Answer:** B

### Topic 1.9 — Method Signatures

#### 1
What two components make up a **method signature**?
A) The method name and the return type.
B) The method name and the ordered list of parameter types.
C) The return type and the visibility modifier (public/private).
D) The parameter names and the method body.
E) The class name and the method name.  
**
**Answer:** B

#### 2
Which of the following statements about **overloaded methods** is true?
A) They must have different names.
B) They must have the same return type.
C) They have the same name but different signatures.
D) They are not allowed in Java.
E) They must be in different classes.  
**
**Answer:** C

#### 3
What is a **formal parameter**?
A) The actual value passed to a method.
B) A variable declared in the method header that receives a value.
C) The return type of a void method.
D) A comment describing the method.
E) A local variable declared inside the method body.  
**
**Answer:** B

#### 4
Which of the following is a **void** method?
A) A method that returns an int.
B) A method that has no parameters.
C) A method that does not return a value.
D) A method that is always private.
E) A method that belongs to the Math class.  
**
**Answer:** C

#### 5
What happens when a **non-void** method is called?
A) It must be called as a standalone statement.
B) It returns a value that can be used in an expression or stored in a variable.
C) It always prints its result to the console.
D) It terminates the program.
E) It returns a boolean value false by default.  
**
**Answer:** B

#### 6
When calling a method, the values passed into the method are called:
A) Formal parameters
B) Signatures
C) Arguments
D) Attributes
E) Methods  
**
**Answer:** C

#### 7
Java uses **call by value** when passing arguments. This means:
A) The method receives a copy of the actual value.
B) The method can change the original variable passed from the caller.
C) Only double values can be passed to methods.
D) The method signature is ignored.
E) All arguments must be literals.  
**
**Answer:** A

#### 8
Consider the following method headers. Which two would be considered **overloaded** if they were in the same class?I. public void calculate(int x)II. public void calculate(double x)III. public int calculate(int x)
A) I and II
B) I and III
C) II and III
D) I, II, and III
E) None of these are overloaded.  
**
**Answer:** A

#### 9
Which of the following is a valid method call for a method with the signature doMath(int x, double y)?
A) doMath(5);
B) doMath(5.0, 2);
C) doMath(5, 2.0);
D) doMath("5", "2.0");
E) doMath(int 5, double 2.0);  
**
**Answer:** C

#### 10
What happens to the execution flow when a method is called?
A) The program stops and waits for user input.
B) The program execution jumps to the called method and returns after the method finishes.
C) The program continues to the next line while the method runs in the background.
D) The compiler re-checks the program for syntax errors.
E) All variables are reset to their default values.  
**
**Answer:** B

### Topic 1.10 — Calling Class Methods

#### 1
Which keyword in a method header indicates that it is a **class (static) method**?
A) void
B) public
C) static
D) class
E) new  
**
**Answer:** C

#### 2
How are class methods typically called from another class?
A) Using the keyword new.
B) Using the class name and the dot operator.
C) Using an object instance and the dot operator.
D) They cannot be called from other classes.
E) By typing the method name only.  
**
**Answer:** B

#### 3
Which of the following is true about **static methods**?
A) They require an object to be instantiated before use.
B) They are associated with the class itself, not individual objects.
C) They can only be called from the java.util package.
D) They cannot have parameters.
E) They always return a double.  
**
**Answer:** B

#### 4
Which of the following is a call to a **class method**?
A) Scanner kbd \= new Scanner(System.in);
B) String s \= "Hello"; s.length();
C) double result \= Math.sqrt(16);
D) myObject.doSomething();
E) int x \= 10;  
**
**Answer:** C

#### 5
If you are calling a static method defined **within the same class**, the class name:
A) Is required.
B) Is optional.
C) Causes a syntax error.
D) Must be replaced by the this keyword.
E) Is only required for void methods.  
**
**Answer:** B

#### 6
Which of the following methods from the Math class is a class method?
A) abs
B) pow
C) sqrt
D) random
E) All of the above.  
**
**Answer:** E

#### 7
Which of the following headers describes a class method that returns an int?
A) public int calculate()
B) public static void calculate()
C) public static int calculate()
D) public calculate(int x)
E) static calculate int()  
**
**Answer:** C

#### 8
Static methods:
A) Can access instance variables of the class.
B) Cannot access instance variables of the class directly.
C) Are only used for mathematical operations.
D) Are created using the instanceof operator.
E) Must always be private.  
**
**Answer:** B

#### 9
What is the result of Math.abs(-10)?
A) \-10
B) 10
C) 0
D) 10.0
E) \-10.0  
**
**Answer:** B

#### 10
A programmer wants to call a method help() which is defined as public static void help(). Which of the following is a valid way to call it?
A) help(); (If called from the same class)
B) ClassName.help(); (From any class)
C) new help();
D) Both A and B are correct.
E) None of the above.  
**
**Answer:** D

### Topic 1.11 — Math Class

#### 1
What is the result of the expression Math.pow(2, 3)?
A) 6.0
B) 8.0
C) 9.0
D) 5.0
E) 8  
**
**Answer:** B

#### 2
What is the range of values produced by Math.random()?
A) 0.0 \<= x \< 1.0
B) 0.0 \< x \<= 1.0
C) 1 \<= x \<= 10
D) 0.0 \<= x \<= 1.0
E) 0 \<= x \< 100  
**
**Answer:** A

#### 3
Which of the following code segments generates a random integer between 1 and 10, inclusive?
A) (int) (Math.random() \* 10)
B) (int) (Math.random() \* 11)
C) (int) (Math.random() \* 10\) \+ 1
D) (int) (Math.random() \* 11\) \+ 1
E) Math.random(1, 10\)  
**
**Answer:** C

#### 4
What is the result of Math.sqrt(25.0)?
A) 5
B) 5.0
C) 625.0
D) 12.5
E) \-5.0  
**
**Answer:** B

#### 5
Which Math method should be used to calculate |-5|?
A) Math.sqrt
B) Math.pow
C) Math.abs
D) Math.random
E) Math.round  
**
**Answer:** C

#### 6
What is the return type of Math.random()?
A) int
B) double
C) boolean
D) String
E) void  
**
**Answer:** B

#### 7
Consider the following code segment:
```java
double x \= \-4.7;
double result \= Math.abs(Math.sqrt(Math.pow(x, 2)));
```
What is the value of result?
A) 4.7
B) \-4.7
C) 22.09
D) 4.0
E) 5.0  
**
**Answer:** A

#### 8
To produce a random integer in the range \[min, max\] (inclusive), which formula is correct?
A) (int) (Math.random() \* (max \- min)) \+ min
B) (int) (Math.random() \* (max \- min \+ 1)) \+ min
C) (int) (Math.random() \* max) \+ min
D) (int) (Math.random() \* min) \+ max
E) Math.random(min, max)  
**
**Answer:** B

#### 9
What is the result of Math.abs(-5.5)?
A) 5
B) 5.5
C) \-5.5
D) 6.0
E) 5.0  
**
**Answer:** B

#### 10
Which of the following Math class methods returns an int?
A) Math.random()
B) Math.sqrt(double x)
C) Math.pow(double a, double b)
D) Math.abs(int x)
E) All Math methods return double.  
**
**Answer:** D

### Topic 1.12 — Objects: Instances of Classes

#### 1
In object-oriented programming, a **class** is best described as:
A) A specific data value.
B) A blueprint or template for creating objects.
C) A collection of loop statements.
D) A physical part of the computer.
E) A single variable.  
**
**Answer:** B

#### 2
An **object** is:
A) The same as a class.
B) An instance of a class.
C) A keyword in Java.
D) A type of syntax error.
E) A primitive data type.  
**
**Answer:** B

#### 3
What is stored in a **reference type** variable?
A) The actual numeric value.
B) A boolean value.
C) The memory address (reference) of an object.
D) The source code of the class.
E) A copy of the JVM.  
**
**Answer:** C

#### 4
Which of the following is a **reference type**?
A) int
B) double
C) String
D) boolean
E) All of the above are reference types.  
**
**Answer:** C

#### 5
All classes in Java are subclasses of which class?
A) Math
B) String
C) System
D) Object
E) Class  
**
**Answer:** D

#### 6
A class hierarchy allows subclasses to draw upon attributes and behaviors of a superclass. This relationship is called:
A) Encapsulation
B) Polymorphism
C) Inheritance
D) Instantiation
E) Sequencing  
**
**Answer:** C

#### 7
Consider a class Car. If we create myCar and yourCar, these are:
A) Two different classes.
B) Two instances of the same class.
C) Two primitive variables.
D) Two static methods.
E) Two attributes of the Object class.  
**
**Answer:** B

#### 8
Which of the following is true about reference variables?
A) They can only refer to String objects.
B) They can be assigned the value null.
C) They take up less memory than int variables.
D) They are automatically converted to boolean.
E) They hold primitive values.  
**
**Answer:** B

#### 9
The attributes of an object are also known as its:
A) Methods
B) State
C) Behaviors
D) Signature
E) Package  
**
**Answer:** B

#### 10
Behaviors of an object are defined by its:
A) Instance variables
B) Class name
C) Methods
D) Constructor signatures
E) Memory address  
**
**Answer:** C

### Topic 1.13 — Object Creation and Storage (Instantiation)

#### 1
Which keyword is used to create a new object in Java?
A) class
B) static
C) new
D) void
E) public  
**
**Answer:** C

#### 2
What is the purpose of a **constructor**?
A) To delete an object from memory.
B) To initialize the initial state of an object.
C) To perform mathematical calculations.
D) To print information to the console.
E) To convert int to double.  
**
**Answer:** B

#### 3
A **constructor signature** consists of:
A) The constructor name and its ordered list of parameter types.
B) The return type and the parameters.
C) The class name and the method body.
D) The keyword new and the class name.
E) The visibility modifier only.  
**
**Answer:** A

#### 4
When multiple constructors with different signatures exist in the same class, they are said to be:
A) Overridden
B) Overloaded
C) Encapsulated
D) Abstracted
E) Static  
**
**Answer:** B

#### 5
If no constructor is written for a class, Java provides a:
A) Syntax error.
B) Postcondition.
C) Default (no-parameter) constructor.
D) Static method.
E) Runtime exception.  
**
**Answer:** C

#### 6
Consider the following code:
```java
Dog myDog \= new Dog("Buddy", 3);
```
What is "Buddy" and 3 in this statement?
A) Formal parameters
B) Instance variables
C) Arguments (actual parameters)
D) Method signatures
E) Literals  
**
**Answer:** C

#### 7
What value is assigned to a reference variable that does not currently point to any object?
A) 0
B) ""
C) null
D) false
E) void  
**
**Answer:** C

#### 8
When a constructor is called, what happens to the program flow?
A) It continues to the next line immediately.
B) It jumps to the constructor code and returns after the constructor finishes.
C) It stops the program permanently.
D) It reloads all classes.
E) It checks for integer overflow.  
**
**Answer:** B

#### 9
Which of the following is a valid constructor call for a class Book that has a constructor Book(String title, int pages)?
A) Book b \= Book("Java", 500);
B) Book b \= new Book(500, "Java");
C) Book b \= new Book("Java", 500);
D) Book b \= new Book("Java");
E) Book b \= new "Java", 500;  
**
**Answer:** C

#### 10
Constructor parameters allow:
A) The user to type values at the keyboard.
B) The caller to provide data to establish the initial state of the object.
C) The method to return multiple values.
D) The compiler to ignore the class.
E) The program to run without a main method.  
**
**Answer:** B

### Topic 1.14 — Calling Instance Methods

#### 1
To call an **instance method**, what must be used?
A) The class name and a colon.
B) The object name and the dot operator.
C) The keyword static.
D) A while loop.
E) The return type only.  
**
**Answer:** B

#### 2
Calling a method on a **null** reference results in:
A) A syntax error.
B) A NullPointerException.
C) The method returning 0.
D) The program skipping the call.
E) An ArithmeticException.  
**
**Answer:** B

#### 3
Consider the code:
```java
Dog d1 \= new Dog();
d1.bark();
```
In this code, bark() is a(n):
A) Class method
B) Instance method
C) Attribute
D) Constructor
E) Variable  
**
**Answer:** B

#### 4
Which of the following is true about instance methods?
A) They can only be called using the class name.
B) they are used to define the behaviors of an object.
C) They must always be public static.
D) They cannot return a value.
E) They are ignored by the JVM.  
**
**Answer:** B

#### 5
If s is a String object, which of the following is a valid call to an instance method?
A) String.length(s);
B) s.length();
C) length(s);
D) new length(s);
E) s-\>length();  
**
**Answer:** B

#### 6
What does the dot operator (.) do in the context of calling instance methods?
A) It marks the end of a statement.
B) It separates the object name from the method being called.
C) It represents a decimal point in a double.
D) It creates a new instance.
E) It is used for comments.  
**
**Answer:** B

#### 7
Instance methods:
A) Have access to the object's instance variables.
B) Cannot use parameters.
C) Must be named the same as the class.
D) Are only used in the Math class.
E) Do not require an object to be instantiated.  
**
**Answer:** A

#### 8
What is the effect of calling a void instance method?
A) It returns a double.
B) It performs an action but does not return a value to the caller.
C) It prints its name to the console.
D) It causes a NullPointerException.
E) It must be used inside a System.out.println statement.  
**
**Answer:** B

#### 9
A method call is considered **legal** if:
A) It matches a method signature in the object's class.
B) It uses the same name as the class.
C) It is written in all capital letters.
D) It contains a semicolon inside the parentheses.
E) It has at least three parameters.  
**
**Answer:** A

#### 10
Consider the code:
```java
Dog d1 \= null;
d1.eat();
```
What happens when this code is executed?
A) The dog eats.
B) The program terminates with a NullPointerException.
C) The dog is instantiated automatically.
D) Nothing happens.
E) A syntax error occurs at compile time.  
**
**Answer:** B

### Topic 1.15 — String Manipulation

#### 1
In Java, a **String** object is:
A) A primitive data type.
B) Immutable (its content cannot be changed after creation).
C) Only able to store numbers.
D) Automatically converted to boolean.
E) A class in the java.util package.  
**
**Answer:** B

#### 2
What is the index of the **first** character in a String?
A) 1
B) 0
C) \-1
D) string.length()
E) It depends on the string.  
**
**Answer:** B

#### 3
What is the value of str after the following code?
```java
String str \= "AP";
str \+= " CSA";
```
A) "AP"
B) " CSA"
C) "AP CSA"
D) "APCSA"
E) An error occurs.  
**
**Answer:** C

#### 4
Consider the code segment:
```java
String s1 \= "cat";
String s2 \= "dog";
System.out.print(s1.compareTo(s2) \< 0);
```
What is printed?
A) true
B) false
C) catdog
D) 0
E) \-1  
**
**Answer:** A

#### 5
```java
If String word \= "Computer";, what is returned by word.substring(2, 5)?
```
A) "omp"
B) "mpu"
C) "mput"
D) "ompu"
E) "Computer"  
**
**Answer:** B

#### 6
What is the result of "Java" \+ 8?
A) 12
B) "Java8"
C) "Java 8"
D) A syntax error.
E) "Java"  
**
**Answer:** B

#### 7
Which method returns the number of characters in a String?
A) size()
B) length()
C) count()
D) index()
E) capacity()  
**
**Answer:** B

#### 8
```java
If String s \= "Hello";, what is s.substring(3)?
```
A) "Hel"
B) "ell"
C) "lo"
D) "llo"
E) "o"  
**
**Answer:** C

#### 9
Which method is used to check if two String objects contain the same sequence of characters?
A) \==
B) equals
C) compareTo
D) indexOf
E) contains  
**
**Answer:** B

#### 10
If s.indexOf("abc") returns \-1, it means:
A) "abc" is at the end of the string.
B) "abc" is at the beginning of the string.
C) "abc" was not found in the string.
D) The string is empty.
E) "abc" occurs exactly once.  
**
**Answer:** C
