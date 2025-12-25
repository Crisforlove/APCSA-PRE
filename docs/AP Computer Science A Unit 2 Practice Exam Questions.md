### Topic 2.1 — Algorithms with Selection and Repetition

#### 1
What is the result of the following code segment?
```java
String s = "ABCDEF";
System.out.println(s.substring(1, 3) + s.substring(4));
```

- A) ABCD
- B) BCDE
- C) BCEF
- D) BCDEF
- E) ABCDEF

**Answer:** C

#### 2
A class SomeMethods already contains the following method signatures: one(int), one(int, int), and one(int, String). Which of the following new method signatures would **NOT** cause a compiler error if added to the class?

- I. one(int value)

- II. one(String first, int second)

- III. one(int first, int second, int third)

- A) I only
- B) I and II only
- C) I and III only
- D) II and III only
- E) I, II, and III

**Answer:** D

#### 3
What is printed as a result of the following call: slope(1, 2, 5, 10);? (Assume the method prints the change in y over change in x as a fraction).

- A) 8/4
- B) 5/1
- C) 4/8
- D) 2/1
- E) 1/5

**Answer:** A

#### 4
Which of the following Java expressions correctly calculates $\\sqrt{\\frac{(x+y)^2}{|a-b|}}$?

- A) Math.sqrt(x^2, y^2, a-b)
- B) Math.sqrt((x+y)^2) / Math.abs(a,b)
- C) Math.sqrt((x+y)^2 / Math.abs(a-b))
- D) Math.sqrt(Math.pow(x+y, 2) / Math.abs(a,b))
- E) Math.sqrt(Math.pow(x+y, 2) / Math.abs(a-b))

**Answer:** E

#### 5
Given a method header public double myMethod(int a, boolean b), which of the following method calls will compile correctly?

- A) int result = myMethod(2, false);
- B) int result = myMethod(2.5, true);
- C) double result = myMethod(0, false);
- D) double result = myMethod(true, 10);
- E) double result = myMethod(2.5, true);

**Answer:** C

#### 6
What is the output of the following code segment?
```java
String str = "comp";
for (int i = 0; i < str.length(); i++) {
System.out.print(str.substring(i) + " ");
}
```

- A) comp
- B) c o m p
- C) comp com co c
- D) comp omp mp p
- E) comp comp comp comp

**Answer:** D

#### 7
Consider the code:
```java
int x = (int)(Math.random() * 5) + 10;
int y = (int)(Math.random() * 10) + 5;
```
Which of the following statements about x and y is true?

- I. There are more possible values for y than for x.

- II. It is possible for x and y to have the same value.

- III. The range of x is a subset of the range of y.

- A) I only
- B) II only
- C) III only
- D) I and III only
- E) I, II, and III

**Answer:** E

#### 8
What is the value of num after the following code is executed?
```java
String str = "CompSci";
str.substring(0, 3);
int num = str.length();
```

- A) 3
- B) 4
- C) 5
- D) 6
- E) 7

**Answer:** E

#### 9
What is printed by the following code?
```java
String str = "0";
str += str + 0 + 8;
System.out.println(str);
```

- A) 8
- B) 08
- C) 008
- D) 0008
- E) Compiler error

**Answer:** D

#### 10
What is printed as a result of executing the following?
```java
int one = 1;
int two = 2;
String zee = "Z";
System.out.println(one + two + zee);
```

- A) 12Z
- B) 3Z
- C) 12zee
- D) 3zee
- E) onetwozee

**Answer:** B

### Topic 2.2 — Boolean Expressions

#### 1
Which of the following expressions evaluates to true if and only if the integer x is between 10 and 20, inclusive?

- A) 10 <= x <= 20
- B) x >= 10 && x <= 20
- C) x >= 10 || x <= 20
- D) !(x < 10) || !(x > 20)
- E) x > 10 && x < 20

**Answer:** B

#### 2
The method containsArt is intended to return true if any of its String parameters contain the substring "art". Which of the following calls demonstrates that the method is buggy (returns true incorrectly)?

- A) containsArt("rattrap", "similar", "today")
- B) containsArt("start", "article", "Bart")
- C) containsArt("harm", "chortle", "crowbar")
- D) containsArt("matriculate", "carat", "arbitrary")
- E) containsArt("darkroom", "cartoon", "articulate")

**Answer:** C

#### 3
Which expression correctly calculates a new average after excluding the lowest grade?

- A) sum / num - 1
- B) sum / (num - 1)
- C) sum - low / (num - 1)
- D) (sum - low) / num - 1
- E) (sum - low) / (num - 1)

**Answer:** E

#### 4
```java
If a method is defined as public void doSomething(), which of the following is a legal way to call it?I. doSomething();II. String s = doSomething();III. System.out.println(doSomething());
```

- A) I only
- B) II only
- C) III only
- D) I and II only
- E) I and III only

**Answer:** A

#### 5
What is the result of \! (5 \> 3 && 2 \<= 2)?

- A) true
- B) false
- C) 5 > 3
- D) 2 <= 2
- E) Syntax error

**Answer:** B

#### 6
Which of the following is equivalent to \!(a || b)?

- A) !a || !b
- B) !a && !b
- C) a && b
- D) !a || b
- E) a || !b

**Answer:** B

#### 7
Given boolean x = true; boolean y = false;, what is the value of x || y && !x?

- A) true
- B) false
- C) null
- D) 0
- E) 1

**Answer:** A

#### 8
Which relational operator is used to test for "not equal to"?

- A) ==
- B) !
- C) !=
- D) <>
- E) /=

**Answer:** C

#### 9
In short-circuit evaluation, the expression A && B will **NOT** evaluate B if:

- A) A is true
- B) A is false
- C) B is true
- D) B is false
- E) A and B are both true

**Answer:** B

#### 10
Which of the following correctly compares two double values d1 and d2 for equality, considering potential rounding errors?

- A) d1 == d2
- B) d1.equals(d2)
- C) Math.abs(d1 - d2) < 0.0001
- D) d1 - d2 == 0
- E) !(d1 != d2)

**Answer:** C

### Topic 2.3 — if Statements

#### 1
Consider the following code segment:
```java
int x = 5;
if (x > 0)
x = x + 1;
if (x > 5)
x = x + 1;
System.out.println(x);
```
What is printed?

- A) 5
- B) 6
- C) 7
- D) 0
- E) 1

**Answer:** C

#### 2
Which of the following best describes the outcome of an if-else statement?

- A) Both blocks of code are executed if the condition is true.
- B) Neither block of code is executed if the condition is false.
- C) Exactly one of the two blocks of code is always executed.
- D) The if block is executed only if the else block fails.
- E) It creates a loop that runs until the condition is false.

**Answer:** C

#### 3
What is printed by the following code?
```java
int a = 10;
int b = 20;
if (a > b)
System.out.print("apple");
System.out.print("banana");
```

- A) apple
- B) banana
- C) applebanana
- D) Nothing is printed
- E) apple banana

**Answer:** B

#### 4
Which code segment will correctly set max to the larger of x and y?

- A) if (x > y) max = x; else max = y;
- B) max = x; if (y > x) max = y;
- C) if (x < y) max = y; else max = x;
- D) All of the above
- E) None of the above

**Answer:** D

#### 5
What is the result of executing the following if score is 85?
```java
if (score >= 90)
grade = "A";
if (score >= 80)
grade = "B";
```

- A) A
- B) B
- C) AB
- D) No value assigned
- E) Compiler error

**Answer:** B

#### 6
Consider the following method intended to return "Renaissance" for years 1400 to 1600 inclusive:
```java
public static String getCategory(int year) {
String category = "Other";
if (year >= 1400 && year <= 1600) {
category = "Renaissance";
}
return category;
}
```
Which of the following calls correctly returns "Renaissance"?

- A) getCategory(1399)
- B) getCategory(1400)
- C) getCategory(1601)
- D) getCategory(1000)
- E) getCategory(1700)

**Answer:** B

#### 7
A programmer forgot the braces {} for an if statement with two lines of code. What type of error is most likely to occur?

- A) Syntax error
- B) Logic error
- C) Runtime error
- D) Overflow error
- E) No error

**Answer:** B

#### 8
If n \= 0, what happens in the following?
```java
if (n != 0 && 10 / n > 1) {
System.out.print("Success");
}
```

- A) It prints Success
- B) It throws an ArithmeticException
- C) It does nothing (the second part is not evaluated)
- D) It throws a NullPointerException
- E) It prints 0

**Answer:** C

#### 9
Which statement is true about the Boolean condition in an if statement?

- A) It must be an assignment using =.
- B) It must evaluate to an int.
- C) It must evaluate to either true or false.
- D) It can only contain variables, not literals.
- E) It is ignored by the compiler if it contains a Math method.

**Answer:** C

#### 10
What is the value of result after this code if val \= \-5?
```java
int result = 0;
if (val < 0)
result = Math.abs(val);
else
result = val;
```

- A) -5
- B) 0
- C) 5
- D) -1
- E) 10

**Answer:** C
