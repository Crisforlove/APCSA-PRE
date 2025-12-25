根据**the sources**（特别是考纲 CED 和你提供的 Unit 3 题目汇总），以下是 **Unit 3: Class Creation** 所有小节（Topic 3.1–3.9）的完整题目集。每小节包含 10 道题目，格式严格遵守选项换行与排版整齐的要求。

### Topic 3.1 — Abstraction and Program Design

**题目数量：10**

#### 1

Which of the following best describes the process of **abstraction** in program design?A) Writing as much code as possible in a single method.B) Hiding irrelevant details and focusing on the main idea to reduce complexity.C) Making all variables public so they can be accessed anywhere.D) Using only primitive data types to save memory.E) Avoiding the use of classes and objects.  
**Answer:** B 1, 2

#### 2

Which Boolean expression is equivalent to (x && y) || (\!x && \!y)?A) The expression is always true.B) The expression is true only when x and y have the same value.C) The expression is true only when x and y are different.D) The expression is always false.E) The expression is equivalent to x || y.  
**Answer:** B 2

#### 3

In a class design for a **Board Game**, which of the following would be considered an **attribute** (represented by an instance variable)?A) playGame()B) movePiece()C) numberOfPlayersD) calculateScore()E) isGameOver()  
**Answer:** C 2, 3

#### 4

**Procedural abstraction** allows a programmer to use a method by:A) Knowing exactly how the method was written line-by-line.B) Knowing what the method does without needing to know how it is implemented.C) Only calling the method if it is static.D) Accessing the private instance variables of the class directly.E) Redefining the method in the main class.  
**Answer:** B 3

#### 5

Which expression simplifies (y \> 10000 && (x \> 1000 || x \< 1500)) || (y \> 10000)?A) y \> 10000B) x \> 1000 || x \< 1500C) y \> 10000 && x \> 1000D) y \> 10000 || x \< 1500E) true  
**Answer:** A 3, 4

#### 6

Breaking down a large behavior of a class into smaller, manageable methods is called:A) EncapsulationB) InheritanceC) Method DecompositionD) InstantiationE) Sequencing  
**Answer:** C 4

#### 7

Which of the following is an example of an **inheritance relationship**?A) A Car has a Tire.B) A Person has a Name.C) A SavingsAccount is a BankAccount.D) A Rectangle has a Width.E) A Student has a Grade.  
**Answer:** C 4

#### 8

According to De Morgan's Law, \!((a \>= b) && \!(c \< d)) is equivalent to:A) (a \< b) || (c \< d)B) (a \< b) && (c \< d)C) (a \>= b) || (c \< d)D) (a \< b) || (c \>= d)E) (a \>= b) && (c \< d)  
**Answer:** A 5

#### 9

A class variable is an attribute that is:A) Unique to each instance of the class.B) Shared by all instances of the class.C) Only accessible within the main method.D) Always a String.E) Declared inside a constructor.  
**Answer:** B 5

#### 10

When designing a program using **top-down programming**, a programmer:A) Writes the lowest-level methods first.B) Writes the code from the first line to the last without planning.C) Defines operations to be performed and then refines them with more detail.D) Makes all methods private to start.E) Only uses recursion.  
**Answer:** C 6

### Topic 3.2 — Impact of Program Design

**题目数量：10**

#### 1

A programmer wants to allow others to use a method they wrote without raising **intellectual property** concerns. What is the best course of action?A) Keep the code on a private server.B) Designate the method as public.C) Publish the code as **open source**.D) Remove the comments from the code.E) Charge a small fee for every call.  
**Answer:** C 6, 7

#### 2

**System reliability** refers to:A) How fast the program runs.B) The program being able to perform tasks as expected without failure under stated conditions.C) The amount of memory the program uses.D) How many comments the programmer wrote.E) The program's ability to compile on any version of Java.  
**Answer:** B 7

#### 3

Which of the following is a potential **unintended consequence** of a program designed to track traffic patterns to improve travel time?A) Shorter commutes for users.B) More efficient fuel use.C) Privacy risks due to collecting location data.D) Better urban planning.E) Reduced road wear.  
**Answer:** C 7, 8

#### 4

If a programmer reuses code that is **not** published as open source:A) It is always legal if they provide a link.B) They must obtain permission and often purchase the code.C) They only need permission if the program makes money.D) It is only an issue if the code has bugs.E) Java's compiler will block the execution.  
**Answer:** B 8

#### 5

Which action is most likely to **maximize system reliability**?A) Testing the program with only the most common inputs.B) Testing the program with a wide variety of conditions, including extreme values.C) Making the code as short as possible.D) Removing all if statements.E) Using only static methods.  
**Answer:** B 8, 9

#### 6

The legal and ethical implications of computer use are important because:A) Programs can have beneficial or harmful impacts on society, economy, and culture.B) It makes the code run faster.C) It is required to pass the Java compiler.D) It prevents syntax errors.E) It allows for infinite loops.  
**Answer:** A 9

#### 7

A program that reads an identification number should check with the specification writer if zero is acceptable as a first digit to avoid:A) Syntax errors.B) Runtime exceptions.C) Logic errors in data interpretation.D) Memory leaks.E) Compiler warnings.  
**Answer:** C 9, 10

#### 8

A **robust program** is one that:A) Never has comments.B) Anticipates and handles types of errors users may make.C) Is written in under 100 lines.D) Uses the most complex algorithms possible.E) Only works on high-end computers.  
**Answer:** B 10

#### 9

Why should a programmer check for **algorithmic bias**?A) To make the program compile faster.B) To ensure the program doesn't create unfair outcomes for specific groups of users.C) To reduce the number of variables.D) To avoid using the Math class.E) To ensure all variables are private.  
**Answer:** B 10, 11

#### 10

When incorporating a third-party library into a project, a "responsible programmer" should first:A) Change all variable names to match their style.B) Check the licensing agreement for usage rights.C) Delete the documentation to save space.D) Make all methods in the library static.E) Only use the library if it is over 10 years old.  
**Answer:** B 11

### Topic 3.3 — Anatomy of a Class

**题目数量：10**

#### 1

In the AP Java subset, which of the following is true about **instance variables**?A) They should be designated as public.B) They belong to the object, and each object has its own copy.C) They are shared by all instances of the class.D) They are declared inside methods.E) They cannot be modified after the constructor runs.  
**Answer:** B 12

#### 2

The technique of keeping implementation details hidden from external classes is called:A) AbstractionB) PolymorphismC) Data EncapsulationD) InheritanceE) Instantiation  
**Answer:** C 12, 13

#### 3

Given the class Apartment with a public method calculateRent() and a private method getTenant(), which call in another class Duplex will compile?A) Apartment.calculateRent()B) Apartment.getTenant()C) unitOne.calculateRent() (where unitOne is an Apartment object)D) unitTwo.getTenant()E) Duplex.calculateRent()  
**Answer:** C 13

#### 4

Which keyword restricts access to the declaring class only?A) publicB) staticC) privateD) finalE) new  
**Answer:** C 13, 14

#### 5

In this course, **classes** are always designated as:A) privateB) protectedC) publicD) staticE) final  
**Answer:** C 14

#### 6

Which diagram represents the most appropriate design for a Movie class with attributes title and rating?A) Public title, public rating; private accessors.B) Public title, public rating; public accessors.C) Private title, private rating; public accessors.D) Private title, private rating; private accessors.E) Static title, static rating; public accessors.  
**Answer:** C 14, 15

#### 7

A **header** for a class in Java typically looks like:A) private class MyClassB) public Class MyClass()C) public class MyClassD) new class MyClassE) static class MyClass  
**Answer:** C 15

#### 8

Which of the following is **NOT** a reason for making instance variables private?A) To achieve encapsulation.B) To prevent external classes from changing data in unexpected ways.C) To allow the internal implementation to change without affecting other classes.D) To make the program compile faster.E) To control how the data is accessed through methods.  
**Answer:** D 15, 16

#### 9

A method designated as **public**:A) Can only be accessed within its own class.B) Can be accessed internally or externally to a class.C) Can only be called by the main method.D) Must return a double.E) Cannot have parameters.  
**Answer:** B 16

#### 10

The default value for an uninitialized instance variable of type **reference (Object)** is:A) 0B) ""C) nullD) falseE) undefined  
**Answer:** C 16

### Topic 3.4 — Constructors

**题目数量：10**

#### 1

What is the purpose of a **constructor** in a class?A) To delete objects from memory.B) To set the initial state of an object by initializing instance variables.C) To perform complex logic calculations.D) To print the class name to the console.E) To convert the class into an interface.  
**Answer:** B 17

#### 2

If a class Rational has constructors Rational(), Rational(int n), and Rational(int n, int d), which call is **invalid**?A) new Rational()B) Rational r \= r1;C) new Rational(2, \-3)D) new Rational(3.5)E) new Rational(10)  
**Answer:** D 17, 18

#### 3

When no constructor is written for a class, Java provides a:A) Syntax error.B) Default (no-parameter) constructor.C) Static method to create objects.D) Copy of the superclass constructor.E) Runtime exception.  
**Answer:** B 18

#### 4

A **constructor signature** consists of:A) The return type and method name.B) The constructor name and the ordered list of parameter types.C) The keyword new and the class name.D) The variable names of the parameters only.E) The visibility modifier and the class name.  
**Answer:** B 18, 19

#### 5

Consider the following Date class constructor: public Date(String m, int d). Which code segment correctly creates an instance?A) Date birthday \= new Date("September", "5th");B) Date birthday \= new Date("September", 5);C) Date birthday \= new Date("September 5");D) Date birthday \= new Date();E) Date birthday \= Date("September", 5);  
**Answer:** B 19

#### 6

When a constructor is called, what is returned?A) A void value.B) The value of the first instance variable.C) A reference to the newly created object.D) The name of the class as a String.E) A Boolean true.  
**Answer:** C 19, 20

#### 7

The relationship where an object contains instance variables is often called a:A) "is-a" relationship.B) "has-a" relationship.C) "can-do" relationship.D) "inherited-from" relationship.E) "static" relationship.  
**Answer:** B 20

#### 8

Constructors are said to be **overloaded** when:A) They have different names.B) They call each other using the super keyword.C) There are multiple constructors with different signatures in the same class.D) They are defined in both a superclass and a subclass.E) They take more than 10 parameters.  
**Answer:** C 20, 21

#### 9

What are the default values for uninitialized instance variables of types int, double, and boolean?A) 1, 1.0, trueB) 0, 0.0, trueC) 0, 0.0, falseD) null, null, nullE) undefined, undefined, undefined  
**Answer:** C 21

#### 10

In a constructor, if an instance variable has the same name as a parameter, you should use which keyword to distinguish them?A) superB) staticC) thisD) newE) void  
**Answer:** C 21

### Topic 3.5 — Methods: How to Write Them

**题目数量：10**

#### 1

A method that performs an action but does **not** return a value is called a:A) Accessor method.B) Mutator method.C) Void method.D) Static method.E) Constructor.  
**Answer:** C 22

#### 2

An **accessor method** is used to:A) Change the value of an instance variable.B) Allow other classes to obtain a copy of the value of an instance variable.C) Delete an object.D) Print the values of all static variables.E) Create a new instance of a class.  
**Answer:** B 22, 23

#### 3

A **mutator (modifier) method** is used to:A) Return a value to the caller.B) Change the values of instance variables.C) Ensure a method cannot be overridden.D) Access private data without changing it.E) Call the constructor.  
**Answer:** B 23

#### 4

When a **primitive value** (like an int) is passed as an argument to a method, the parameter is initialized with:A) A reference to the original variable.B) A copy of the value.C) The memory address of the caller.D) A null value.E) An automatically widened double.  
**Answer:** B 23, 24

#### 5

What happens when a return statement is executed inside a method?A) The method continues to the next line.B) The program terminates immediately.C) The flow of control returns to the point where the method was called.D) All variables in the class are reset.E) A new object is created.  
**Answer:** C 24

#### 6

Which of the following is a correct header for a **mutator** method that sets the age of a person?A) public int setAge(int a)B) public void getAge()C) public void setAge(int a)D) private int setAge(int a)E) static void setAge(int a)  
**Answer:** C 24, 25

#### 7

Which of the following is a correct header for an **accessor** method that returns a person's name?A) public void getName()B) public String getName()C) private String getName()D) public String setName(String n)E) static String getName()  
**Answer:** B 25

#### 8

Any code written sequentially **after** a return statement in the same block will:A) Run normally.B) Only run if an exception occurs.C) Never be executed.D) Cause a syntax error in some IDEs.E) Both C and D.  
**Answer:** E 25, 26

#### 9

A method with the header public double calculate(int x) is considered:A) A void method.B) A non-void method.C) A constructor.D) A static factory.E) A private helper.  
**Answer:** B 26

#### 10

If temp is an int variable with value 5, and it is passed to a method doWork(int n) which changes n to 10, what is the value of temp after the call?A) 10B) 5C) 0D) 15E) null  
**Answer:** B 26

### Topic 3.6 — Methods: Passing and Returning References

**题目数量：10**

#### 1

Given the following situation: one \== two is true, and two.equals(three) is false. A code segment contains three if statements testing these references. What is the output?A) No lines are printed.B) **Only "one dot equals two" is printed.**C) Both "one dot equals two" and "two dot equals three" are printed.D) "one \== two" is printed, but no equals methods are called.E) All three test lines are printed.  
**Answer:** B 27, 28

#### 2

In the GameClass, which has private fields numPlayers and gameOver, but public methods addPlayer() and endGame(), which of the following code segments are valid when called from an external class?I. game.numPlayers++;II. game.addPlayer();III. game.gameOver();IV. game.endGame();A) I and II onlyB) II and III onlyC) **II and IV only**D) I and IV onlyE) II, III, and IV only  
**Answer:** C 28

#### 3

A method is intended to move anActor from its current grid to a new grid at the same location. Which sequence of method calls is correct?A) Put the actor in the new grid, then remove it from the old grid.B) Remove the actor from the old grid, then put it in the new grid.C) **removeSelfFromGrid(); followed by putSelfInGrid(newGrid, loc);**D) Use a while loop to copy the actor's coordinates.E) Reassign the grid reference without calling any methods.  
**Answer:** C 28, 29

#### 4

If d1 and d2 are references to the same Date object (aliases), and d2.addYears(1); is called, what happens to the object referenced by d1?A) It remains unchanged.B) **It is also incremented by one year because both variables point to the same memory address.**C) It becomes null.D) A Compile-time error occurs due to multiple references.E) A new Date object is automatically created for d1.  
**Answer:** B 29

#### 5

Which of the following descriptions accurately identifies the relationship between the variable vehicle and the class Car?A) vehicle is an attribute of the Car class.B) **vehicle is an instance of the Car class.**C) Car is an instance of the vehicle object.D) vehicle is a static method within Car.E) Car is a primitive data type stored in vehicle.  
**Answer:** B 29, 30

#### 6

A method timesTwo(int n) is called using an Integer object val that stores the value 10\. What is the result?A) A Type mismatch error occurs.B) **The Integer is autounboxed to 10, the method returns 20, and it is printed.**C) The method returns 10 because Integer is immutable.D) The program throws a NullPointerException.E) The method must be changed to timesTwo(Integer n).  
**Answer:** B 30

#### 7

Which is the correct way to construct a WindTurbine object with an initial efficiencyRating of 0.25?A) **WindTurbine wt \= new WindTurbine(0.25);**B) WindTurbine wt \= 0.25;C) new WindTurbine wt(0.25);D) WindTurbine wt.setEfficiency(0.25);E) wt \= WindTurbine.new(0.25);  
**Answer:** A 30, 31

#### 8

To create an instance of a Point2D class with coordinates (3.0, 4.0), which statement is required?A) Point2D p \= (3.0, 4.0);B) Point2D p \= Point2D(3.0, 4.0);C) **Point2D p \= new Point2D(3.0, 4.0);**D) new Point2D(3.0, 4.0); (without assignment)E) p \= new Point2D(); p.x \= 3.0; p.y \= 4.0;  
**Answer:** C 31

#### 9

A Person object student is initialized with the name "Thomas". What is the most appropriate way to change its name to "Tom"?A) student \= "Tom";B) student.myName \= "Tom";C) student.getName("Tom");D) **student.setName("Tom");**E) Person.setName("Tom");  
**Answer:** D 31, 32

#### 10

Which of the following statements about attributes and instances is true?A) A class is an instance of its attributes.B) **Attributes (data) are stored in variables within an instance of a class.**C) A reference variable stores the actual data of an object.D) Methods are instances of class behaviors.E) All attributes must be public static.  
**Answer:** B 32

### Topic 3.7 — Class Variables and Methods

**题目数量：10**

#### 1

Which keyword is used to designate that a variable or method belongs to the **class** rather than an instance?A) publicB) privateC) **static**D) finalE) void  
**Answer:** C 33

#### 2

A programmer attempts to overload an average method. Which of the following sets of headers will compile without error in the same class?I. average(int, int) and average(int, int)II. average(int, int) and average(int, int, int)III. average(int, int) and average(double, double)A) I onlyB) II onlyC) III onlyD) **II and III only**E) I, II, and III  
**Answer:** D 33, 34

#### 3

Given a class SomeClass with a non-static method getA(), which of the following calls from an external class will compile?A) SomeClass.getA();B) **obj.getA(); (where obj is an instance of SomeClass)**C) int x \= getA(obj);D) SomeClass.obj.getA();E) new getA();  
**Answer:** B 34

#### 4

Which of the following best describes a **class variable**?A) A variable unique to every object.B) **A variable shared by all instances of the class.**C) A variable that can only be used in the main method.D) A variable that cannot be private.E) A local variable inside a constructor.  
**Answer:** B 34, 35

#### 5

If a static method calculateAverage is defined in class MathUtils, how should it be called from another class?A) MathUtils mu \= new MathUtils(); mu.calculateAverage();B) **MathUtils.calculateAverage();**C) calculateAverage();D) mu.calculateAverage();E) new MathUtils.calculateAverage();  
**Answer:** B 35

#### 6

What is the effect of the final keyword when applied to a class variable?A) The variable becomes static.B) **The variable's value cannot be modified after initialization.**C) The variable is hidden from subclasses.D) The variable must be a String.E) The variable can only be used in while loops.  
**Answer:** B 35, 36

#### 7

Which of the following is true about static methods?A) They can directly access instance variables.B) **They cannot access instance variables or instance methods without an object reference.**C) They are called using the new keyword.D) They cannot have parameters.E) They must always return a double.  
**Answer:** B 36

#### 8

Consider a class Thing with a static method greet(). If a is an instance of Thing, which call is valid?I. a.greet();II. Thing.greet();A) I onlyB) II onlyC) **Both I and II**D) Neither I nor IIE) Only if greet() is void.  
**Answer:** C 36, 37

#### 9

A class uses a class variable to keep track of the total number of Student objects created. Where should the incrementing of this variable occur?A) In a static method.B) **In the class constructors.**C) In the main method.D) In a final method.E) Inside an if statement in the class header.  
**Answer:** B 37

#### 10

Can a class method call another class method in the same class?A) No, static methods are independent.B) **Yes, by using the method name directly or the class name.**C) Only if the second method is private.D) Only if the call is inside a for loop.E) Yes, but only if they have different return types.  
**Answer:** B 37, 38

### Topic 3.8 — Scope and Access

**题目数量：10**

#### 1

Where can a **local variable** be accessed?A) Anywhere in the class.B) **Only within the block of code (like a method or loop) where it is declared.**C) Only within the constructor.D) In any subclass of the current class.E) By any external class using the dot operator.  
**Answer:** B 38

#### 2

If a method parameter has the same name as an instance variable, what does the name refer to within that method?A) The instance variable.B) **The parameter (local variable).**C) Both variables simultaneously.D) The compiler will report an error.E) The static version of the variable.  
**Answer:** B 38, 39

#### 3

What is the **scope** of a formal parameter?A) The entire class.B) **The method in which it is defined.**C) Only the line where it is initialized.D) The main method.E) Global scope.  
**Answer:** B 39

#### 4

Which of the following is true about private access?A) Private variables are visible to subclasses.B) **Private variables and methods are only accessible within the class they are declared.**C) Private methods cannot have parameters.D) Private variables are automatically static.E) External classes can access private fields using getters.  
**Answer:** B 39, 40

#### 5

A programmer wants to ensure that a Student object's gpa can be read by other classes but not modified directly. What is the best design?A) Make gpa public.B) Make gpa private and provide no methods.C) **Make gpa private and provide a public getter (accessor) method.**D) Make gpa public and static.E) Make gpa private and provide a public setter (mutator) method.  
**Answer:** C 40

#### 6

What happens if you try to declare a local variable as public?A) It becomes accessible to all classes.B) **A compiler error occurs (local variables cannot have access modifiers).**C) It is treated as an instance variable.D) It is only visible to the main method.E) It remains local but is shared by all loops.  
**Answer:** B 40, 41

#### 7

Which statement is true about equals and \== for String comparison?A) They are identical in all cases.B) \== checks content, equals checks memory address.C) **\== checks memory address, equals checks character sequence.**D) equals is only for integers.E) \== is faster and always preferred.  
**Answer:** C 41

#### 8

In a class hierarchy, can a subclass access the private instance variables of its superclass?A) Yes, because it is a child class.B) **No, private variables are restricted to the declaring class.**C) Only if the subclass is in the same package.D) Only if the variable is also static.E) Yes, by using the this keyword.  
**Answer:** B 41, 42

#### 9

A method calculate() is defined inside a class. It calls printResult() which is also in the same class. This is legal because:A) Both are in the same scope.B) **Instance methods can call other instance methods of the same class.**C) calculate() is automatically static.D) printResult() is a constructor.E) Java requires all methods to be public.  
**Answer:** B 42

#### 10

A variable declared inside the body of a for loop:A) Can be used after the loop ends.B) **Has a scope limited to that for loop.**C) Is an instance variable.D) Must be static.E) Cannot be an int.  
**Answer:** B 42, 43

### Topic 3.9 — this Keyword

**题目数量：10**

#### 1

What does the keyword this refer to?A) The superclass of the current object.B) **The current object instance whose method or constructor is being called.**C) The static variables of the class.D) The first parameter of a method.E) The main method.  
**Answer:** B 43

#### 2

When is using this required?A) To call any instance method.B) **To distinguish between an instance variable and a parameter with the same name.**C) To create a new object.D) To access a public static variable.E) Inside every String method.  
**Answer:** B 43, 44

#### 3

Consider the following constructor:  
public Person(String name) {  
    this.name \= name;  
}  
What is the purpose of this.name?A) To create a new local variable.B) **To assign the value of the parameter name to the instance variable name.**C) To call the Person constructor recursively.D) To make the name static.E) To convert the string to an object.  
**Answer:** B 44

#### 4

Can this be used in a static (class) method?A) Yes, to access static variables.B) **No, because static methods are not associated with a specific instance.**C) Only if the method is public.D) Yes, but only in the Math class.E) Only if it is passed as a parameter.  
**Answer:** B 44, 45

#### 5

Which of the following is a valid use of this to pass the current object as an argument?A) calculate(Person this);B) **calculate(this);**C) this.calculate();D) calculate(new this);E) Person(this);  
**Answer:** B 45

#### 6

Inside a method of class Thing, the call this.talk() is equivalent to:A) Thing.talk()B) **talk()**C) new talk()D) a.talk()E) super.talk()  
**Answer:** B 45

#### 7

When this is used in a constructor, it must:A) Be the last line.B) **Refer to the object being instantiated.**C) Be static.D) Return a void value.E) Be followed by the new keyword.  
**Answer:** B 45, 46

#### 8

If a method returns this, what is the return type of the method?A) void) intC) **The class type itself (the reference type).**D) ObjectE) boolean  
**Answer:** C 46

#### 9

In the Date class, a method addYears(int n) modifies the current object. Which statement accurately describes the role of this here?A) this is a copy of the date.B) **this allows the method to access and modify the fields of the specific object that called it.**C) this prevents other objects from being created.D) this makes the method static.E) this is used to call the constructor of the Object class.  
**Answer:** B 46, 47

#### 10

Which of the following best represents the use of this to call another constructor in the same class (constructor chaining)?A) this.Constructor();B) **this(parameters);**C) new this(parameters);D) this \= new Class(parameters);E) call this(parameters);  
**Answer:** B 47  
**Analogy for Unit 3:**Building a class is like **designing a blueprint for a smartphone**:

* **Topic 3.1-3.3 (Abstraction & Anatomy)**: You decide what the phone *has* (screen, battery \- **attributes**) and what it *does* (make calls, take photos \- **behaviors**). 48  
* **Topic 3.4 (Constructors)**: This is the **factory assembly line** that sets the initial settings (brightness, volume) when a new phone is boxed. 48  
* **Topic 3.5-3.6 (Methods & References)**: These are the **apps and buttons**. Passing a reference is like **sharing a Google Doc link**—both people can see and edit the same document. 48  
* **Topic 3.7 (Class Variables)**: This is like the **cellular network**—all phones of this model share the same network status. 48  
* **Topic 3.8-3.9 (Scope & this)**: **Scope** is the privacy of your text messages (local vs global), and **this** is the phone referring to itself (e.g., "This phone's battery is low"). 48

