### Topic 3.1 — Abstraction and Program Design

#### 1
Which of the following best describes the process of **abstraction** in program design?

- A) Writing as much code as possible in a single method.
- B) Hiding irrelevant details and focusing on the main idea to reduce complexity.
- C) Making all variables public so they can be accessed anywhere.
- D) Using only primitive data types to save memory.
- E) Avoiding the use of classes and objects.

**Answer:** B

#### 2
Which Boolean expression is equivalent to (x && y) || (\!x && \!y)?

- A) The expression is always true.
- B) The expression is true only when x and y have the same value.
- C) The expression is true only when x and y are different.
- D) The expression is always false.
- E) The expression is equivalent to x || y.

**Answer:** B

#### 3
In a class design for a **Board Game**, which of the following would be considered an **attribute** (represented by an instance variable)?

- A) playGame()
- B) movePiece()
- C) numberOfPlayers
- D) calculateScore()
- E) isGameOver()

**Answer:** C

#### 4
**Procedural abstraction** allows a programmer to use a method by:

- A) Knowing exactly how the method was written line-by-line.
- B) Knowing what the method does without needing to know how it is implemented.
- C) Only calling the method if it is static.
- D) Accessing the private instance variables of the class directly.
- E) Redefining the method in the main class.

**Answer:** B

#### 5
Which expression simplifies (y \> 10000 && (x \> 1000 || x \< 1500)) || (y \> 10000)?

- A) y > 10000
- B) x > 1000 || x < 1500
- C) y > 10000 && x > 1000
- D) y > 10000 || x < 1500
- E) true

**Answer:** A

#### 6
Breaking down a large behavior of a class into smaller, manageable methods is called:

- A) Encapsulation
- B) Inheritance
- C) Method Decomposition
- D) Instantiation
- E) Sequencing

**Answer:** C

#### 7
Which of the following is an example of an **inheritance relationship**?

- A) A Car has a Tire.
- B) A Person has a Name.
- C) A SavingsAccount is a BankAccount.
- D) A Rectangle has a Width.
- E) A Student has a Grade.

**Answer:** C

#### 8
According to De Morgan's Law, \!((a \>= b) && \!(c \< d)) is equivalent to:

- A) (a < b) || (c < d)
- B) (a < b) && (c < d)
- C) (a >= b) || (c < d)
- D) (a < b) || (c >= d)
- E) (a >= b) && (c < d)

**Answer:** A

#### 9
A class variable is an attribute that is:

- A) Unique to each instance of the class.
- B) Shared by all instances of the class.
- C) Only accessible within the main method.
- D) Always a String.
- E) Declared inside a constructor.

**Answer:** B

#### 10
When designing a program using **top-down programming**, a programmer:

- A) Writes the lowest-level methods first.
- B) Writes the code from the first line to the last without planning.
- C) Defines operations to be performed and then refines them with more detail.
- D) Makes all methods private to start.
- E) Only uses recursion.

**Answer:** C

### Topic 3.2 — Impact of Program Design

#### 1
A programmer wants to allow others to use a method they wrote without raising **intellectual property** concerns. What is the best course of action?

- A) Keep the code on a private server.
- B) Designate the method as public.
- C) Publish the code as open source.
- D) Remove the comments from the code.
- E) Charge a small fee for every call.

**Answer:** C

#### 2
**System reliability** refers to:

- A) How fast the program runs.
- B) The program being able to perform tasks as expected without failure under stated conditions.
- C) The amount of memory the program uses.
- D) How many comments the programmer wrote.
- E) The program's ability to compile on any version of Java.

**Answer:** B

#### 3
Which of the following is a potential **unintended consequence** of a program designed to track traffic patterns to improve travel time?

- A) Shorter commutes for users.
- B) More efficient fuel use.
- C) Privacy risks due to collecting location data.
- D) Better urban planning.
- E) Reduced road wear.

**Answer:** C

#### 4
If a programmer reuses code that is **not** published as open source:

- A) It is always legal if they provide a link.
- B) They must obtain permission and often purchase the code.
- C) They only need permission if the program makes money.
- D) It is only an issue if the code has bugs.
- E) Java's compiler will block the execution.

**Answer:** B

#### 5
Which action is most likely to **maximize system reliability**?

- A) Testing the program with only the most common inputs.
- B) Testing the program with a wide variety of conditions, including extreme values.
- C) Making the code as short as possible.
- D) Removing all if statements.
- E) Using only static methods.

**Answer:** B

#### 6
The legal and ethical implications of computer use are important because:

- A) Programs can have beneficial or harmful impacts on society, economy, and culture.
- B) It makes the code run faster.
- C) It is required to pass the Java compiler.
- D) It prevents syntax errors.
- E) It allows for infinite loops.

**Answer:** A

#### 7
A program that reads an identification number should check with the specification writer if zero is acceptable as a first digit to avoid:

- A) Syntax errors.
- B) Runtime exceptions.
- C) Logic errors in data interpretation.
- D) Memory leaks.
- E) Compiler warnings.

**Answer:** C

#### 8
A **robust program** is one that:

- A) Never has comments.
- B) Anticipates and handles types of errors users may make.
- C) Is written in under 100 lines.
- D) Uses the most complex algorithms possible.
- E) Only works on high-end computers.

**Answer:** B

#### 9
Why should a programmer check for **algorithmic bias**?

- A) To make the program compile faster.
- B) To ensure the program doesn't create unfair outcomes for specific groups of users.
- C) To reduce the number of variables.
- D) To avoid using the Math class.
- E) To ensure all variables are private.

**Answer:** B

#### 10
When incorporating a third-party library into a project, a "responsible programmer" should first:

- A) Change all variable names to match their style.
- B) Check the licensing agreement for usage rights.
- C) Delete the documentation to save space.
- D) Make all methods in the library static.
- E) Only use the library if it is over 10 years old.

**Answer:** B

### Topic 3.3 — Anatomy of a Class

#### 1
In the AP Java subset, which of the following is true about **instance variables**?

- A) They should be designated as public.
- B) They belong to the object, and each object has its own copy.
- C) They are shared by all instances of the class.
- D) They are declared inside methods.
- E) They cannot be modified after the constructor runs.

**Answer:** B

#### 2
The technique of keeping implementation details hidden from external classes is called:

- A) Abstraction
- B) Polymorphism
- C) Data Encapsulation
- D) Inheritance
- E) Instantiation

**Answer:** C

#### 3
Given the class Apartment with a public method calculateRent() and a private method getTenant(), which call in another class Duplex will compile?

- A) Apartment.calculateRent()
- B) Apartment.getTenant()
- C) unitOne.calculateRent() (where unitOne is an Apartment object)
- D) unitTwo.getTenant()
- E) Duplex.calculateRent()

**Answer:** C

#### 4
Which keyword restricts access to the declaring class only?

- A) public
- B) static/Users/criswang/Desktop/题目总集/AP CSA MCQ/generated
- C) private
- D) final
- E) new

**Answer:** C

#### 5
In this course, **classes** are always designated as:

- A) private
- B) protected
- C) public
- D) static
- E) final

**Answer:** C

#### 6
Which diagram represents the most appropriate design for a Movie class with attributes title and rating?

- A) Public title, public rating; private accessors.
- B) Public title, public rating; public accessors.
- C) Private title, private rating; public accessors.
- D) Private title, private rating; private accessors.
- E) Static title, static rating; public accessors.

**Answer:** C

#### 7
A **header** for a class in Java typically looks like:

- A) private class MyClass
- B) public Class MyClass()
- C) public class MyClass
- D) new class MyClass
- E) static class MyClass

**Answer:** C

#### 8
Which of the following is **NOT** a reason for making instance variables private?

- A) To achieve encapsulation.
- B) To prevent external classes from changing data in unexpected ways.
- C) To allow the internal implementation to change without affecting other classes.
- D) To make the program compile faster.
- E) To control how the data is accessed through methods.

**Answer:** D

#### 9
A method designated as **public**:

- A) Can only be accessed within its own class.
- B) Can be accessed internally or externally to a class.
- C) Can only be called by the main method.
- D) Must return a double.
- E) Cannot have parameters.

**Answer:** B

#### 10
The default value for an uninitialized instance variable of type **reference (Object)** is:

- A) 0
- B) ""
- C) null
- D) false
- E) undefined

**Answer:** C

### Topic 3.4 — Constructors

#### 1
What is the purpose of a **constructor** in a class?

- A) To delete objects from memory.
- B) To set the initial state of an object by initializing instance variables.
- C) To perform complex logic calculations.
- D) To print the class name to the console.
- E) To convert the class into an interface.

**Answer:** B

#### 2
If a class Rational has constructors Rational(), Rational(int n), and Rational(int n, int d), which call is **invalid**?

- A) new Rational()
- B) new Rational(10)
- C) new Rational(2, -3)
- D) new Rational(3.5)
- E) Rational r = r1;

**Answer:** D

#### 3
When no constructor is written for a class, Java provides a:

- A) Syntax error.
- B) Default (no-parameter) constructor.
- C) Static method to create objects.
- D) Copy of the superclass constructor.
- E) Runtime exception.

**Answer:** B

#### 4
A **constructor signature** consists of:

- A) The return type and method name.
- B) The constructor name and the ordered list of parameter types.
- C) The keyword new and the class name.
- D) The variable names of the parameters only.
- E) The visibility modifier and the class name.

**Answer:** B

#### 5
Consider the following Date class constructor: public Date(String m, int d). Which code segment correctly creates an instance?

- A) Date birthday = new Date("September", "5th");
- B) Date birthday = new Date("September", 5);
- C) Date birthday = new Date("September 5");
- D) Date birthday = new Date();
- E) Date birthday = Date("September", 5);

**Answer:** B

#### 6
When a constructor is called, what is returned?

- A) A void value.
- B) The value of the first instance variable.
- C) A reference to the newly created object.
- D) The name of the class as a String.
- E) A Boolean true.

**Answer:** C

#### 7
The relationship where an object contains instance variables is often called a:

- A) "is-a" relationship.
- B) "has-a" relationship.
- C) "can-do" relationship.
- D) "inherited-from" relationship.
- E) "static" relationship.

**Answer:** B

#### 8
Constructors are said to be **overloaded** when:

- A) They have different names.
- B) They call each other using the super keyword.
- C) There are multiple constructors with different signatures in the same class.
- D) They are defined in both a superclass and a subclass.
- E) They take more than 10 parameters.

**Answer:** C

#### 9
What are the default values for uninitialized instance variables of types int, double, and boolean?

- A) 1, 1.0, true
- B) 0, 0.0, true
- C) 0, 0.0, false
- D) null, null, null
- E) undefined, undefined, undefined

**Answer:** C

#### 10
In a constructor, if an instance variable has the same name as a parameter, you should use which keyword to distinguish them?

- A) super
- B) static
- C) this
- D) new
- E) void

**Answer:** C

### Topic 3.5 — Methods: How to Write Them

#### 1
A method that performs an action but does **not** return a value is called a:

- A) Accessor method.
- B) Mutator method.
- C) Void method.
- D) Static method.
- E) Constructor.

**Answer:** C

#### 2
An **accessor method** is used to:

- A) Change the value of an instance variable.
- B) Allow other classes to obtain a copy of the value of an instance variable.
- C) Delete an object.
- D) Print the values of all static variables.
- E) Create a new instance of a class.

**Answer:** B

#### 3
A **mutator (modifier) method** is used to:

- A) Return a value to the caller.
- B) Change the values of instance variables.
- C) Ensure a method cannot be overridden.
- D) Access private data without changing it.
- E) Call the constructor.

**Answer:** B

#### 4
When a **primitive value** (like an int) is passed as an argument to a method, the parameter is initialized with:

- A) A reference to the original variable.
- B) A copy of the value.
- C) The memory address of the caller.
- D) A null value.
- E) An automatically widened double.

**Answer:** B

#### 5
What happens when a return statement is executed inside a method?

- A) The method continues to the next line.
- B) The program terminates immediately.
- C) The flow of control returns to the point where the method was called.
- D) All variables in the class are reset.
- E) A new object is created.

**Answer:** C

#### 6
Which of the following is a correct header for a **mutator** method that sets the age of a person?

- A) public int setAge(int a)
- B) public void getAge()
- C) public void setAge(int a)
- D) private int setAge(int a)
- E) static void setAge(int a)

**Answer:** C

#### 7
Which of the following is a correct header for an **accessor** method that returns a person's name?

- A) public void getName()
- B) public String getName()
- C) private String getName()
- D) public String setName(String n)
- E) static String getName()

**Answer:** B

#### 8
Any code written sequentially **after** a return statement in the same block will:

- A) Run normally.
- B) Only run if an exception occurs.
- C) Never be executed.
- D) Cause a syntax error in some IDEs.
- E) Both C and D.

**Answer:** E

#### 9
A method with the header public double calculate(int x) is considered:

- A) A void method.
- B) A non-void method.
- C) A constructor.
- D) A static factory.
- E) A private helper.

**Answer:** B

#### 10
If temp is an int variable with value 5, and it is passed to a method doWork(int n) which changes n to 10, what is the value of temp after the call?

- A) 10
- B) 5
- C) 0
- D) 15
- E) null

**Answer:** B
