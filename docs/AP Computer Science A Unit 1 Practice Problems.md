### Topic 1.1 — Introduction to Algorithms, Programming, and Compilers

#### 1
Which of the following best describes the difference between a **syntax error** and a **logic error**?

- A) A syntax error is found by the programmer during testing, while a logic error is found by the compiler.
- B) A syntax error prevents the program from compiling, while a logic error allows the program to run but produces incorrect results.
- C) A syntax error occurs during the execution of the program, while a logic error occurs before the program starts.
- D) A logic error is always an ArithmeticException, while a syntax error is always a NullPointerException.
- E) There is no difference; both terms refer to the same type of programming mistake.

**Answer:** B

#### 2
A programmer is writing a program and forgets to include a semicolon at the end of a line. What will happen when the programmer attempts to compile and run the code?

- A) The program will run normally but ignore the line without the semicolon.
- B) The program will run and then throw a runtime exception when it reaches that line.
- C) The compiler will report a syntax error, and the program will not run.
- D) The computer will automatically insert the missing semicolon and run the program.
- E) The program will produce a logic error and output "null".

**Answer:** C

#### 3
Which of the following is an example of a **runtime error**?

- A) Missing a closing brace } in a class definition.
- B) Using a variable name that has not been declared.
- C) An attempt to divide an integer by zero while the program is executing.
- D) Writing a formula for the area of a square as side + side instead of side * side.
- E) Typing System.out.print as system.out.print (lowercase 's').

**Answer:** C

#### 4
Which of the following statements about **algorithms** is true?

- A) Algorithms can only be represented using Java code.
- B) An algorithm is a step-by-step process used to solve a problem or complete a task.
- C) Algorithms are only used for mathematical calculations.
- D) Every algorithm must contain at least one if statement and one while loop.
- E) Algorithms are executed by the compiler, not the computer's processor.

**Answer:** B

#### 5
A programmer wants to calculate the average of three numbers but writes the expression as a \+ b \+ c / 3.0 instead of (a \+ b \+ c) / 3.0. What type of error is this?

- A) Syntax error
- B) Logic error
- C) Runtime error
- D) Overflow error
- E) Rounding error

**Answer:** B

#### 6
What is the primary role of a **compiler** in the Java programming environment?

- A) To execute the program line by line and show the output.
- B) To allow the user to type in code and save it as a file.
- C) To check the code for syntax errors and translate it into a format the computer can execute.
- D) To automatically fix logic errors in the programmer's algorithms.
- E) To provide a graphical user interface for the application.

**Answer:** C

#### 7
Which of the following would be detected by a Java compiler?

- A) A variable name that is spelled differently than its declaration.
- B) A loop that never terminates (infinite loop).
- C) A calculation that results in a negative number when a positive was expected.
- D) A formula that uses the wrong mathematical operator.
- E) A user entering "abc" when the program expects an integer.

**Answer:** A

#### 8
What term describes a specific type of runtime error that interrupts the normal flow of a program’s execution?

- A) Logic flaw
- B) Syntax break
- C) Compilation warning
- D) Exception
- E) Algorithm drift

**Answer:** D

#### 9
In an **Integrated Development Environment (IDE)**, which tool is typically used to write the source code?
- A) The Compiler
- B) The Text Editor
- C) The Debugger
- D) The Virtual Machine
- E) The Output Console

**Answer:** B

#### 10
The order in which steps are completed in an algorithm is known as:

- A) Selection
- B) Iteration
- C) Sequencing
- D) Abstraction
- E) Encapsulation

**Answer:** C

### Topic 1.2 — Variables and Data Types

#### 1
The code segment below is intended to calculate the circumference c of a circle with the diameter d of 1.5. The circumference of a circle is equal to its diameter times pi. Which of the following variable declarations are most appropriate to replace /* missing declarations */ in this code segment?
```java
/* missing declarations */
circumference = diameter * 3.14159;
```

- A) int diameter = 1.5; int circumference;
- B) int diameter = 1; double circumference;
- C) double diameter = 1.5; double circumference;
- D) double diameter = 1.5; int circumference;
- E) int diameter = 1.5; double circumference;

**Answer:** C

#### 2
Consider the following code segment.
```java
double d = 20.5;
int i = /* missing code */;
```
Which of the following can be used to replace /* missing code */ so that the code segment will compile?

- I. (int) d;

- II. (int) (d + 0.5);

- III. d;

- A) I only
- B) II only
- C) I and II only
- D) II and III only
- E) I, II, and III

**Answer:** C

#### 3
A code segment is intended to determine the number of players whose average score in a game exceeds 0.5. A player’s average score is stored in avgScore, and the number of players who meet the criterion is stored in the variable count. Which of the following pairs of declarations is most appropriate for the code segment described?

- A) int avgScore; int count;
- B) int avgScore; double count;
- C) double avgScore; int count;
- D) double avgScore; double count;
- E) boolean avgScore; int count;

**Answer:** C

#### 4
The following code segment is intended to interchange the values of the int variables x and y. Assume that x and y have been properly declared and initialized.
```java
int temp = x;
/* missing code */
y = temp;
```
Which of the following can be used to replace /* missing code */ so that the code segment works as intended?

- A) x = y;
- B) y = x;
- C) temp = y;
- D) x = temp;
- E) y = temp;

**Answer:** A

#### 5
Consider the following code segment.
```java
double a = 10.0;
double b = 20.0;
double c = a;
a = b;
b = c;
double d = a;
```
What is the value of d after the code segment is executed?

- A) 10.0
- B) 14.0
- C) 20.0
- D) 20.5
- E) 26.0

**Answer:** C

#### 6
Consider the following code segment, where k and count are properly declared and initialized int variables.
```java
k = 2;
```
/* missing code */
```java
count = count + k;
```
Which of the following best describes the behavior of the code segment if /* missing code */ is empty?

- A) The code segment leaves both k and count unchanged.
- B) The code segment increases both k and count by 2.
- C) The code segment increases k by 4 and count by 2.
- D) The code segment leaves k unchanged and increases count by 2.
- E) The code segment increases k by 2 and leaves count unchanged.

**Answer:** D

#### 7
According to the AP Java subset, which of the following is **NOT** a primitive data type?

- A) int
- B) double
- C) boolean
- D) String
- E) All of the above are primitive types.

**Answer:** D

#### 8
Consider the following code segment:
```java
int a = 11;
int b = 4;
System.out.print(a / b);
```
What is printed as a result of executing the code segment?

- A) 2.75
- B) 3
- C) 2
- D) 0.75
- E) 11/4

**Answer:** C

#### 9
Consider the following statement:
```java
int i = x % 50;
```
If x is a positive integer, which of the following could **NOT** be the value of i after the statement above executes?

- A) 0
- B) 10
- C) 25
- D) 49
- E) 50

**Answer:** E

#### 10
Which of the following best describes what is stored in a variable of a **reference type**?

- A) The actual numeric value of the data.
- B) The memory address where the object is stored.
- C) A copy of the object's code.
- D) The data type of the object.
- E) The name of the class.

**Answer:** B

### Topic 1.3 — Expressions and Output

#### 1
Consider the following code segment.
```java
System.out.println("apple");
System.out.print("banana");
System.out.println("cherry");
System.out.print("date");
```
What is printed as a result of executing the code segment?

- A) applebananacherrydate
- B) applebananacherrydate
- C) applebananacherrydate
- D) applebananacherrydate
- E) applebananacherrydate

**Answer:** B

#### 2
What is the value of the expression 2 \+ 3 \* 12 / 4 \- 1?

- A) 14
- B) 10
- C) 11
- D) 9
- E) 12

**Answer:** B

#### 3
Consider the following code segment.
```java
int x = 10;
int y = 3;
double z = x / y;
System.out.print(z);
```
What is printed as a result of executing the code segment?

- A) 3.3333333333333335
- B) 3.0
- C) 3
- D) 0.3
- E) 3.33

**Answer:** B

#### 4
Which of the following code segments will print the string He said "Hello"?

- A) System.out.print("He said "Hello"");
- B) System.out.print("He said \\"Hello\\"");
- C) System.out.print("He said \\Hello\\");
- D) System.out.print("He said " + "Hello"");
- E) System.out.print("He said \\\\"Hello\\\\"");

**Answer:** B

#### 5
What is the result of the expression 17 % 5?

- A) 3
- B) 0.4
- C) 2
- D) 5
- E) 1

**Answer:** C

#### 6
What will be output by the following code?
```java
System.out.print("1 + 2 = ");
System.out.println(1 + 2);

```
- A) 1 + 2 = 1 + 2
- B) 1 + 2 = 3
- C) 3 = 3
- D) 1 + 2 = 12
- E) 1+2=3

**Answer:** B

#### 7
Consider the following code segment:
```java
int a = 10;
int b = 20;
System.out.print(a + b + " is the sum");
```
What is printed?

- A) 1020 is the sum
- B) a + b is the sum
- C) 30 is the sum
- D) 10 20 is the sum
- E) 30is the sum

**Answer:** C

#### 8
Consider the following code segment:
```java
System.out.print("Sum: " + 10 + 20);
```
What is printed?

- A) Sum: 30
- B) Sum: 1020
- C) Sum: 10 20
- D) Sum: 10+20
- E) 30

**Answer:** B

#### 9
Which of the following is printed by the statement System.out.println("\\\\\\\\\*\\\\\\\\")?

- A) *\\\\
- B) *
- C) *
- D) *\\\\
- E) *\\\\\\\\

**Answer:** A

#### 10
What is the result of 10 / 4.0?

- A) 2
- B) 2.5
- C) 3
- D) 2.0
- E) 0.4

**Answer:** B

### Topic 1.4 — Assignment Statements and Input

#### 1
Consider the following code segment.
```java
int x = 10;
int y = x;
x = 20;
System.out.print(x + " " + y);
```
What is printed?

- A) 10 10
- B) 20 20
- C) 20 10
- D) 10 20
- E) x y

**Answer:** C

#### 2
Which of the following is the correct way to initialize an int variable named count with the value 0?

- A) count = 0;
- B) int count = 0;
- C) count int = 0;
- D) 0 = int count;
- E) int 0 = count;

**Answer:** B

#### 3
What happens when you use a variable that has been declared but not initialized in an expression?

- A) The program uses a default value of 0.
- B) The program uses a random value from memory.
- C) The compiler will report an error.
- D) The program will crash at runtime with a NullPointerException.
- E) The variable will be automatically initialized to null.

**Answer:** C

#### 4
Which operator is used to assign a value to a variable in Java?

- A) ==
- B) :=
- C) =
- D) ->
- E) <-

**Answer:** C

#### 5
Consider the following code segment.
```java
int p = 5;
int q = 2;
p = p + q;
q = p - q;
p = p - q;
```
What are the values of p and q after this code executes?

- A) p = 5, q = 2
- B) p = 2, q = 5
- C) p = 7, q = 5
- D) p = 7, q = 2
- E) p = 2, q = 2

**Answer:** B

#### 6
A programmer wants to read a word from the keyboard using the Scanner class. Which method should be called?

- A) nextInt()
- B) nextDouble()
- C) next()
- D) nextLine()
- E) readWord()

**Answer:** C

#### 7
Which statement about the Scanner class is true?

- A) It is automatically available in every Java program.
- B) It belongs to the java.lang package.
- C) It requires an import java.util.Scanner; statement.
- D) It can only read data from text files, not the keyboard.
- E) It can only read String values.

**Answer:** C

#### 8
Consider the following code segment.
```java
String s = null;
System.out.print(s);
```
What is printed?

- A) Nothing
- B) null
- C) An error occurs
- D) ""
- E) 0

**Answer:** B

#### 9
A variable of a **primitive type** holds:

- A) A memory address.
- B) A reference to an object.
- C) The actual value.
- D) A copy of the class file.
- E) A pointer to the JVM.

**Answer:** C

#### 10
In the statement x = 10 + 5;, which part is the **expression**?

- A) x
- B) =
- C) 10 + 5
- D) x = 10 + 5
- E) ;

**Answer:** C

### Topic 1.5 — Casting and Range of Variables

#### 1
Consider the following code segment.
```java
double q = 15.0;
int r = 2;
double x = (int) (q / r);
double y = q / r;
System.out.println(x + " " + y);
```
What is printed as a result of executing this code segment?

- A) 7.0 7.0
- B) 7.0 7.5
- C) 7.5 7.0
- D) 7.5 7.5
- E) 7 7.5

**Answer:** B

#### 2
What is the result of the expression (int) 3.9 \+ (int) 2.1?

- A) 6
- B) 5
- C) 5.0
- D) 6.0
- E) 5.1

**Answer:** B

#### 3
Which of the following will result in an **integer overflow**?

- A) Integer.MAX\_VALUE + 1
- B) Integer.MIN\_VALUE - 1
- C) 10 / 0
- D) Both A and B
- E) A, B, and C

**Answer:** D

#### 4
How many bytes of memory are used to store an int value in Java?

- A) 2 bytes
- B) 4 bytes
- C) 8 bytes
- D) 1 byte
- E) 16 bytes

**Answer:** B

#### 5
What is the value of Integer.MAX\_VALUE?

- A) 2^31
- B) 2^31 - 1
- C) 2^32
- D) 2^32 - 1
- E) 1,000,000,000

**Answer:** B

#### 6
Which of the following correctly rounds a positive double x to the nearest integer?

- A) (int) x
- B) (int) (x + 0.5)
- C) (int) (x - 0.5)
- D) (double) (x + 0.5)
- E) Math.round(x) (Note: Though valid in Java, CED focus is on (int)(x + 0.5))

**Answer:** B

#### 7
Consider the following code segment:
```java
int a = 10;
double b = 10.7;
int d = a + (int) b;
```
What is the value of d?

- A) 20
- B) 21
- C) 20.7
- D) 20.0
- E) This code will not compile.

**Answer:** A

#### 8
Which of the following represents an **automatic widening conversion**?

- A) int x = 10.5;
- B) double y = 10;
- C) int z = (int) 10.5;
- D) boolean b = 1;
- E) double w = (double) 10 / 4;

**Answer:** B

#### 9
What is the result of (int) \-3.9?

- A) -4
- B) -3
- C) 3
- D) 4
- E) -3.0

**Answer:** B

#### 10
If you need to represent a value that could exceed 2 billion, which data type should you use (though outside AP subset)?

- A) int
- B) double
- C) boolean
- D) long
- E) int[]

**Answer:** D
