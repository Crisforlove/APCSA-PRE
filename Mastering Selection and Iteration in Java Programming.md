### Topic 2.4 — Nested if Statements

#### 1
Which of the following new method signatures would **NOT** cause a compiler error if added to a class already containing one(int), one(int, int), and one(int, String)?I. one(String first, int second)II. one(int first, int second, int third)III. one(int value)
A) I only
B) II only
C) **I and II only**
D) I and III only
E) II and III only  
**
**Answer:** C

#### 2
```java
What is printed as a result of the following call to a method that uses a nested helper: slope(1, 2, 5, 10);?
```
A) **8/4**
B) 5/1
C) 4/8
D) 2/1
E) 1/5  
**
**Answer:** A

#### 3
Consider x \= (int)(Math.random() \* 5\) \+ 10 and y \= (int)(Math.random() \* 10\) \+ 5\. In a nested if structure, is it possible for x \== y to evaluate to true?
A) **Yes, because the ranges overlap between 10 and 14\.**
B) No, because x is always larger than y.
C) No, because y is always larger than x.
D) Yes, but only if both are 5.
E) Yes, but only if both are 15\.  
**
**Answer:** A

#### 4
Which of the following calls demonstrates that a nested if method intended to find "art" is buggy?
A) containsArt("rattrap", "similar", "today")
B) containsArt("start", "article", "Bart")
C) **containsArt("harm", "chortle", "crowbar")**
D) containsArt("matriculate", "carat", "arbitrary")
E) containsArt("darkroom", "cartoon", "articulate")  
**
**Answer:** C

#### 5
A multi-way selection structure is used to assign grades. If score is 85, which block will execute?
```java
if (score \>= 90\) grade \= "A";
else if (score \>= 80\) grade \= "B";
else grade \= "F";
```
A) The "A" block
B) **The "B" block**
C) Both "A" and "B" blocks
D) The "F" block
E) No block executes  
**
**Answer:** B

#### 6
The following method is intended to return "Renaissance" for years from 1400 to 1600, inclusive. Which code segment correctly replaces /\* missing code \*/?
A) **if (year \> 1600 || year \< 400\) { category \= "Other"; } else if (year \>= 1400\) { category \= "Renaissance"; }**
B) if (year \>= 1400\) { category \= "Renaissance"; } if (year \>= 400\) { category \= "Medieval"; }
C) if (year \< 1400\) { category \= "Other"; } else { category \= "Renaissance"; }
D) category \= "Renaissance"; if (year \< 1400\) category \= "Other";
E) None of the above.  
**
**Answer:** A

#### 7
In a nested if statement, when is the **inner** Boolean expression evaluated?
A) Only if the outer expression is false.
B) **Only if the outer expression is true.**
C) It is always evaluated first.) It is evaluated regardless of the outer condition.
E) Only if the entire program compiles without warnings.  
**
**Answer:** B

#### 8
Which of the following describes a **multi-way selection** (if-else-if)?
A) Every block whose condition is true will execute.
B) Only the else block is guaranteed to execute.
C) **No more than one segment of code is executed based on the first expression that evaluates to true.**
D) It is used to repeat code until a condition is met.
E) It is only used with String objects.  
**
**Answer:** C

#### 9
What is the output of the following nested logic?
```java
String s \= "comp";
if (s.length() \> 3\) {
if (s.substring(0,2).equals("co")) {
System.out.print("match");
}
}
```
A) comp
B) **match**
C) co
D) Nothing is printed
E) Compiler error  
**
**Answer:** B

#### 10
Consider the code segment:
```java
int x \= 1, y \= 2;
String z \= "Z";
if (x \+ y \> 2\) {
if (z.equals("Z")) {
System.out.print(x \+ y \+ z);
}
}
```
A) 12Z
B) **3Z**
C) 12zee
D) 3zee
E) onetwozee  
**
**Answer:** B

### Topic 2.5 — Compound Boolean Expressions

#### 1
Given x \= 12 and y \= 10 from the previous random ranges, which statement is true?I. y \< xII. x \== yIII. x \<= 14 && y \>= 5
A) I only
B) II only
C) I and II only
D) II and III only
E) **I and III only**  
**
**Answer:** E

#### 2
A method containsArt incorrectly returns true for which input due to a logical error in its compound expression?
A) ("start", "article", "Bart")
B) **("harm", "chortle", "crowbar")**
C) ("rattrap", "similar", "today")
D) ("darkroom", "cartoon", "articulate")
E) ("matriculate", "carat", "arbitrary")  
**
**Answer:** B

#### 3
What is the correct order of precedence for evaluating logical operators in Java?
A) &&, ||, \!
B) ||, &&, \!
C) **\!, &&, ||**
D) \!, ||, &\&
E) They all have the same precedence.  
**
**Answer:** C

#### 4
In the expression (A &&
B) , if A is **false**, does the computer evaluate B?
A) Yes, always.
B) **No, this is called short-circuit evaluation.**
C) Only if B is a method call.
D) Only if the program is running in debug mode.
E) Yes, but only if B is a boolean variable.  
**
**Answer:** B

#### 5
In the expression (A ||
B) , if A is **true**, does the computer evaluate B?
A) Yes, to check if it's also true.
B) **No, because the entire expression is already true.**
C) Only if A is a literal.
D) Only if B contains a comparison.
E) Yes, always.  
**
**Answer:** B

#### 6
The expression \!a evaluates to true when:
A) a is true.
B) **a is false.**
C) a is null.
D) a is an integer.
E) a is a String.  
**
**Answer:** B

#### 7
When does a && b evaluate to true?
A) When a is true.
B) When b is true.
C) When at least one of them is true.
D) **When both a and b are true.**
E) When both a and b are false.  
**
**Answer:** D

#### 8
When does a || b evaluate to true?
A) Only when both are true.
B) Only when exactly one is true.
C) **When a is true, b is true, or both are true.**
D) When at least one is false.
E) When both are false.  
**
**Answer:** C

#### 9
What is the result of 1 \+ 2 \+ "0008"?
A) 120008
B) **30008**
C) 000812
D) 00083
E) Compiler error  
**
**Answer:** B

#### 10
```java
Which Java expression correctly represents $\\sqrt{\\frac{(x+y)^2}{|a-b|}}$ using compound Math calls?
```
A) Math.sqrt(x+y, 2 / Math.abs(a-b))
B) Math.sqrt((x+y)^2) / Math.abs(a-b)
C) Math.sqrt(Math.pow(x+y, 2\) / (a-b))
D) **Math.sqrt(Math.pow(x+y, 2\) / Math.abs(a-b))**
E) Math.sqrt(Math.pow(x+y, 2)) / Math.abs(a-b)  
**
**Answer:** D

### Topic 2.6 — Comparing Boolean Expressions

#### 1
Which of the following is equivalent to \!x || \!y || z according to De Morgan's Laws and Boolean logic?
A) \!(x && y) && z
B) **\!(x && y) || z**
C) \!(x || y) && z
D) \!(x || y) || z
E) \! (x && y && z)  
**
**Answer:** B

#### 2
Two Boolean expressions are considered **equivalent** if:
A) They use the same variable names.
B) They are both written on one line.
C) **They evaluate to the same value in all possible cases.**
D) They both contain at least one && operator.
E) They are both true when the program starts.  
**
**Answer:** C

#### 3
According to **De Morgan’s Law**, \!(a && b) is equivalent to:
A) \!a && \!b
B) **\!a || \!b**
C) a || b
D) \! (a || b)
E) a && \!b  
**
**Answer:** B

#### 4
According to **De Morgan’s Law**, \!(a || b) is equivalent to:
A) \!a || \!b
B) **\!a && \!b**
C) a && b
D) \! (a && b)
E) \!a || b  
**
**Answer:** B

#### 5
Which operator is used to test if two different variables hold **references** to the same object?
A) .equals()
B) **\==**
C) \=
D) \!= (to test if they are same)
E) instanceof  
**
**Answer:** B

#### 6
What is the recommended way to compare two double values d1 and d2 to account for rounding errors?
A) d1 \== d2
B) d1.equals(d2)
C) **Math.abs(d1 \- d2) \< 0.0001**
D) (int)d1 \== (int)d2
E) d1 \- d2 \== 0  
**
**Answer:** C

#### 7
Which statement is true about x \= \[10..14\] and y \= \[5..14\]?
A) The ranges are identical.
B) **The range of x is a subset of the range of y.**
C) There is no overlap between the ranges.
D) x has more possible values than y.
E) y can never be 10\.  
**
**Answer:** B

#### 8
If str \= "CompSci", what is the result of str.substring(0,3).length() \== 3?
A) **true**
B) false
C) 3
D) Comp
E) Compiler error  
**
**Answer:** A

#### 9
In the context of String comparison, one.equals(two) checks for:
A) Whether they are the same object in memory.
B) **Whether they contain the same sequence of characters.**
C) Whether their lengths are equal.
D) Whether they both start with "one".
E) Whether they are both null.  
**
**Answer:** B

#### 10
What does obj \== null check for?
A) If the object has a value of 0.
B) If the object is an empty string.
C) **If the reference variable is not associated with any object.**
D) If the object has been deleted from the hard drive.
E) If the object's attributes are all false.  
**
**Answer:** C

### Topic 2.7 — while Loops

#### 1
What is the result of a loop that sums Double values d1, d2, d3, d4 totaling 100.0?
A) **100.0**
B) 10.050.040.0
C) 10.020.070.0
D) 10.020.030.040.0
E) Compiler error  
**
**Answer:** A

#### 2
A while loop calculates a 5% bonus on an initial score of 80.0. What is printed?
A) 4.0
B) 5.0
C) 80.0
D) 84.0
E) **85.0** (if iterative logic adds 5 twice/bonus logic)  
**
**Answer:** E

#### 3
Which function call sequence in a loop initializes x to 11?
A) function2(4,5) \+ function1(1,3)
B) function1(4,5) \+ function2(1,3)
C) function1(4,5) \+ function2(3,1)
D) **function1(3,1) \+ function2(4,5)**
E) function2(3,1) \+ function1(4,5)  
**
**Answer:** D

#### 4
In a GameClass, which statement is valid inside a loop?
A) game.numPlayers++; (if private)
B) **game.addPlayer();**
C) game.gameOver(); (if private)
D) **game.endGame();**
E) B and D only  
**
**Answer:** E

#### 5
What is the best code segment to simulate the sum of two 1..6 dice rolls in a loop?
A) 2 \* (int)(Math.random()\*6)
B) 2 \* (int)(Math.random()\*7)
C) (int)(Math.random()\*6) \+ (int)(Math.random()\*6)
D) (int)(Math.random()\*13)
E) **2 \+ (int)(Math.random()\*6) \+ (int)(Math.random()\*6)**  
**
**Answer:** E

#### 6
To move anActor to a new grid at the same location, which while loop sequence is correct?
A) Put in newGrid then remove from old.
B) Remove from old then put in new.
C) **removeSelfFromGrid(); putSelfInGrid(newGrid, loc);**
D) oldGrid.remove(loc); newGrid.put(anActor, loc);
E) newGrid.put(anActor, loc); oldGrid.remove(loc);  
**
**Answer:** C

#### 7
A loop calculates hours between mile markers m1 and m2 at 60 mph. Which is correct?
A) (|m1|-|m2|)/60.0
B) |m1 \- m2/60.0|
C) **Math.abs(m1 \- m2) / 60.0**
D) Math.abs((m1 \- m2)/60)
E) (double)(Math.abs(m1 \- m2) / 60\)  
**
**Answer:** C

#### 8
When does an **infinite loop** occur?
A) When the condition is initially false.
B) **When the condition always evaluates to true.**
C) When the loop body contains an if statement.
D) When the loop variable is a double.
E) When the programmer uses System.out.print.  
**
**Answer:** B

#### 9
What is an **off-by-one error**?
A) A syntax error found by the compiler.
B) **When a loop iterates one time too many or one time too few.**
C) When a variable is initialized to 1 instead of 0.
D) When the program crashes due to division by zero.
E) When the loop condition uses && instead of ||.  
**
**Answer:** B

#### 10
If the Boolean expression in a while loop initially evaluates to **false**:
A) The loop runs once then stops.
B) The program throws an exception.
C) **The loop body will not execute at all.**
D) The compiler reports an error.
E) The variable is incremented anyway.  
**
**Answer:** C

### Topic 2.8 — for Loops

#### 1
Which for loop update would correctly generate random integers in the range 1, 2 inclusive?
A) (int)(Math.random() \* 25\) \+ 36
B) (int)(Math.random() \* 25\) \+ 60
C) (int)(Math.random() \* 26\) \+ 60
D) **(int)(Math.random() \* 36\) \+ 25**
E) (int)(Math.random() \* 60\) \+ 25  
**
**Answer:** D

#### 2
Which for loop header successfully assigns a random integer from 1 to 10?
A) (int)(Math.random()) \* 10
B) (int)(Math.random()) \* 10 \+ 1
C) (int)(Math.random() \* 10)
D) **(int)(Math.random() \* 10\) \+ 1**
E) (int)(Math.random() \+ 1\) \* 10  
**
**Answer:** D

#### 3
What is the standard formula to produce a random integer in the range \[min, max\] inclusive within a for loop?
A) (int)(Math.random() \* max) \+ min
B) (int)(Math.random() \* max) \+ min \- 1
C) (int)(Math.random() \* (max \- min)) \+ min
D) (int)(Math.random() \* (max \- min)) \+ 1
E) **(int)(Math.random() \* (max \- min \+ 1)) \+ min**  
**
**Answer:** E

#### 4
Which code generates a random integer in the range \[a, 2a\] inclusive?
A) (int)(Math.random() \* a)
B) a \+ (int)(Math.random() \* (a \- 1))
C) a \+ (int)(Math.random() \* 2a)
D) **a \+ (int)(Math.random() \* (a \+ 1))**
E) (int)(Math.random() \* 2a) \+ a  
**
**Answer:** D

#### 5
A for loop generates uniform values r such that 0.5 \<= r \< 5.5. Which is correct?
A) r \= Math.random() \* 5.5;
B) r \= Math.random() \* 5.0;
C) r \= Math.random() \* 6.0 \- 0.5;
D) **r \= Math.random() \* 5.0 \+ 0.5;**
E) r \= Math.random() \* 0.5 \+ 5.0;  
**
**Answer:** D

#### 6
What does scramble("compiler", 3\) return when using a for loop based algorithm?
A) compiler
B) pilercom
C) ilercom
D) **ilercomp**
E) exception  
**
**Answer:** D

#### 7
Which is a correct output for printSum(5, 10.0) called in a for loop?
A) 15
B) 15 / 50
C) 15 / 50.0
D) **15.0**
E) Compiler error  
**
**Answer:** D

#### 8
A for loop builds result \= last char of word2 \+ first two of word1. What is result.indexOf(str2)?
A) **0**
B) 1
C) 2
D) \-1
E) str2.length()  
**
**Answer:** A

#### 9
```java
In a for loop, Double y \= x/2.0; y /= 2; for x \= 3 returns?
```
A) 0.0
B) 0.5
C) **0.75**
D) 1.0
E) 1.5  
**
**Answer:** C

#### 10
The three parts of a for loop header are:
A) Initialization, Declaration, Update.
B) **Initialization, Boolean expression, Update.**
C) Declaration, Condition, Incrementor.
D) Start, Stop, Step.
E) Variable, Range, Method.  
**
**Answer:** B

### Topic 2.9 — Implementing Selection and Iteration Algorithms

#### 1
Which standard algorithm is used to determine the frequency of a criterion?
A) Sorting
B) **Counting in a loop with an if statement**
C) Finding the minimum
D) Rounding doubles
E) Concatenating strings  
**
**Answer:** B

#### 2
Which of the following is **NOT** a standard algorithm mentioned in Unit 2?
A) Identify Individual digits in an integer.
B) Determine a minimum or maximum value.
C) Compute a sum or average.
D) **Identify if a String is a palindrome using Recursion.**
E) Identify if an integer is evenly divisible by another.  
**
**Answer:** D

#### 3
To identify the individual digits of an integer n, which operator is most useful in a loop?
A) \+
B) \*
C) **%**
D) \==
E) Math.sqrt  
**
**Answer:** C

#### 4
What is the result of (int) (Math.random() \* 10\) \+ 1 executed 100 times to find the maximum?
A) **10**
B) 1
C) 11
D) 100
E) 0  
**
**Answer:** A

#### 5
A loop calculates the sum of all integers between 1 and n. This is an example of which standard algorithm?
A) Selection
B) **Computing a sum**
C) Finding frequency
D) Digit identification
E) Rounding  
**
**Answer:** B

#### 6
Which Student constructor call is valid for an algorithm initializing a list?
A) new Student()
B) **new Student("Juan", 15\)**
C) new Student("Juan", "15")
D) new Student(15, "Juan")
E) Student("Juan", 15\)  
**
**Answer:** B

#### 7
Which added Bird constructor causes a conflict (duplicate signature)?
A) Bird()
B) Bird(boolean cf)
C) Bird(String col, String str)
D) Bird(boolean cf, String str, String col)
E) **Bird(String col, String str, boolean cf)** (matches existing String, String, boolean)  
**
**Answer:** E

#### 8
To change a Person object's name to "Tom", which is best?
A) student.myName \= "Tom";
B) student.getName("Tom");
C) **student.setName("Tom");**
D) Person.setName("Tom");
E) new Person("Tom", 1995);  
**
**Answer:** C

#### 9
In a selection algorithm, what is the result of "A" \+ (1 \+ 2)?
A) A12
B) **A3**
C) 3
A) A 3
E) Compiler error  
**
**Answer:** B

#### 10
A processWords algorithm always returns index **0** because:
A) The string is empty.
B) **The searched character is placed at the start of the result string.**
C) The character is not found (-1).
D) The character is at the very end.
E) Strings in Java always start with '0'.  
**
**Answer:** B

### Topic 2.10 — Implementing String Algorithms

#### 1
What is the result of s.substring(1, 3\) \+ s.substring(4) for s \= "ABCDEF"?
A) ABCD
B) BCDE
C) **BCEF**
D) BCDEF
E) ABCDEF  
**
**Answer:** C

#### 2
A standard string algorithm to **reverse** a string typically involves:
A) A single if statement.
B) **Iterating through the string and building a new string backwards.**
C) Calling Math.reverse().
D) Using the \+ operator on two integers.
E) Deleting the first character until the string is empty.  
**
**Answer:** B

#### 3
What is the result of an algorithm that checks if a substring exists?
A) An integer count.
B) **A Boolean value (true or false).**
C) A new String object.
D) A NullPointerException.
E) A double value.  
**
**Answer:** B

#### 4
Which method is essential for determining the number of substrings that meet a specific criteria?
A) Math.random()
B) System.out.println()
C) **String.substring() and a loop**
D) new Object()
E) Integer.MAX\_VALUE  
**
**Answer:** C

#### 5
In processWords, if str2 is the last char of word2, and result \= str2 \+ str1, what is result.indexOf(str2)?
A) **0**
B) 1
C) 2
D) \-1
E) str2.length()  
**
**Answer:** A

#### 6
```java
What is the outcome of Double y \= 3 / 2.0; y /= 2;?
```
A) 0.0
B) 0.5
C) **0.75**
D) 1.0
E) 1.5  
**
**Answer:** C

#### 7
scramble("compiler", 3\) performs a left rotation. The result is:
A) compiler
B) pilercom
C) ilercom
D) **ilercomp**
E) exception  
**
**Answer:** D

#### 8
If str \= "0", what is str \+= str \+ 0 \+ 8?
A) 8
B) 08
C) 008
D) **0008**
E) Compiler error  
**
**Answer:** D

#### 9
Why does str.substring(0, 3\) not change the value of str?
A) The indices are wrong.
B) **String objects are immutable.**
C) The method only works on integers.
D) You must call System.out.print to save it.
E) The result is always null.  
**
**Answer:** B

#### 10
Which overloading is valid for string processing?
A) average(int, int) and average(int, int)
B) **average(int, String) and average(String, int)**
C) average(int, int) and average(int value1, int value2)
D) average(String s) and average(String str)
E) None are valid.  
**
**Answer:** B

### Topic 2.11 — Nested Iteration

#### 1
What is produced by the following nested loop?
```java
for (int j \= 4; j \> 0; j--) {
for (int k \= 0; k \< j; k++) {
System.out.print(k \+ " ");
}
System.out.println();
}
```
A) **0 1 2 3 / 0 1 2 / 0 1 / 0**
B) 0 1 2 3 / 1 2 3 / 2 3 / 3
C) 4 3 2 1 / 4 3 2 / 4 3 / 4
D) 0 / 0 1 / 0 1 2 / 0 1 2 3
E) 4 / 3 / 2 / 1  
**
**Answer:** A

#### 2
How many times will hello be printed?
```java
int j \= 1;
while (j \< 4\) {
for (int k \= 0; k \<= 4; k++) {
System.out.println("hello");
}
j++;
}
```
A) 12
B) **15** (3 iterations of while \* 5 iterations of for)
C) 16
D) 20
E) 25  
**
**Answer:** B

#### 3
In a nested iteration, when does the **inner** loop finish all its iterations?
A) Only after the outer loop finishes.
B) **Before the outer loop can continue to its next iteration.**
C) At the same time as the outer loop.
D) It only runs once regardless of the outer loop.
E) Only if a Boolean expression is false.  
**
**Answer:** B

#### 4
If the outer loop runs N times and the inner loop runs M times for each outer iteration, what is the total count?
A) N \+ M
B) **N \* M**
C) N^M
D) M^N
E) N  
**
**Answer:** B

#### 5
A nested loop is used to investigate modified segments. After investigating a different version, students share conclusions. This is known as:
A) Tracing
B) **Jigsaw activity**
C) Debugging
D) Compiling
E) Casting  
**
**Answer:** B

#### 6
What is the result of puzzle(3) involving nested logic?
A) 0.0
B) 0.5
C) **0.75**
D) 1.0
E) 1.5  
**
**Answer:** C

#### 7
Which nested loop generates random coordinates in \[1, 2\] for both x and y?
A) Outer uses (int)(Math.random()\*36)+25, Inner uses (int)(Math.random()\*25)+60.
B) **Both loops use (int)(Math.random()\*36)+25.**
C) Both loops use (int)(Math.random()\*25)+36.
D) Both loops use (int)(Math.random()\*60)+25.
E) Outer uses Math.random(), Inner uses Math.abs().  
**
**Answer:** B

#### 8
A nested loop produces uniform r values. What range does r \= d \* 5.0 \+ 0.5 cover?
A) 0.0 \<= r \< 1.0
B) 0.5 \<= r \< 5.0
C) **0.5 \<= r \< 5.5**
D) 5.0 \<= r \< 5.5
E) 0.0 \<= r \< 5.5  
**
**Answer:** C

#### 9
Nested for loops are used to scramble("compiler", 3). The number of substring calls is:
A) 1
B) 2
C) **Determined by the loop limit (e.g., 3\)**
D) Always 8
E) 0  
**
**Answer:** C

#### 10
In the Thing class, a.greet() calls talk() twice then name(). If this is called inside an outer loop of 5, how many total calls to talk() are made?
A) 2
B) 5
C) **10**
D) 15
E) 20  
**
**Answer:** C

### Topic 2.12 — Informal Run-Time Analysis

#### 1
```java
How many times will System.out.println("hello"); execute in the nested loop with j \< 4 and k \<= 4?
```
A) 12
B) **15**
C) 16
D) 20
E) 24  
**
**Answer:** B

#### 2
What does a **statement execution count** indicate?
A) The number of lines in the program.
B) **The number of times a specific statement is executed by the program.**
C) The amount of memory used by the statement.
D) The time it took to compile the statement.
E) The number of variables in the statement.  
**
**Answer:** B

#### 3
Which of the following compiles and has the lowest execution cost for accessing myA?
A) **int x \= obj.getA();**
B) int x; obj.getA(x);
C) int x \= obj.myA; (if private)
D) int x \= SomeClass.getA(); (if non-static)
E) int x \= getA(obj);  
**
**Answer:** A

#### 4
Identifying happyBirthday as an instance of Song is part of which analysis?
A) Runtime speed
B) **Object instantiation analysis**
C) Floating point precision
D) Boolean logic
E) String reversal  
**
**Answer:** B

#### 5
Creating a Student object using new Student(id, grade) involves which process?
A) Selection
B) Iteration
C) **Instantiation**
D) De-identification
E) Casting  
**
**Answer:** C

#### 6
What is the complexity of simulating a dice sum using 2 \+ (int)(Math.random()\*6) \+ (int)(Math.random()\*6)?
A) It depends on the dice value.
B) **Constant time (one expression evaluation).**
C) Linear time.
D) Quadratic time.
E) It never finishes.  
**
**Answer:** B

#### 7
```java
Analyzing the sequence removeSelfFromGrid(); putSelfInGrid(newGrid, loc); is an example of:
```
A) **Informal run-time comparison of iterative statements.**
B) Formal big-O notation.
C) Syntax checking.
D) Memory leak detection.
E) Hard drive optimization.  
**
**Answer:** A

#### 8
```java
The calculation hours \= Math.abs(marker1 \- marker2) / 60.0; executes in:
```
A) **Constant time.**
B) Time proportional to marker1.
C) Time proportional to hours.
D) Exponential time.
E) Logarithmic time.  
**
**Answer:** A

#### 9
Determining that origin is an instance of OrderedPair helps in:
A) Calculating sums.
B) **Determining which methods are legal to call.**
C) Reducing the number of variables.
D) Speeding up the compiler.
E) Formatting strings.  
**
**Answer:** B

#### 10
If you have two loops, one with bounds 0 to 10 and another 0 to 100, which has a higher execution count?
A) Bound 0 to 10.
B) **Bound 0 to 100\.**
C) They are the same.
D) It depends on the variable name.
E) It depends on the Math class.  
**
**Answer:** B
