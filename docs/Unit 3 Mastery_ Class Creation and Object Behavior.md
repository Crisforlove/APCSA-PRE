### Topic 3.6 — Methods: Passing and Returning References of an Object

#### 1
Given the following situation: one \== two is true, and two.equals(three) is false. A code segment contains three if statements testing these references. What is the output?

- A) No lines are printed.
- B) Only "one dot equals two" is printed.
- C) Both "one dot equals two" and "two dot equals three" are printed.
- D) "one == two" is printed, but no equals methods are called.
- E) All three test lines are printed.

**Answer:** B

#### 2
In the GameClass, which has private fields numPlayers and gameOver, but public methods addPlayer() and endGame(), which of the following code segments are valid when called from an external class?

- I. game.numPlayers++;

- II. game.addPlayer();

- III. game.gameOver();

- IV. game.endGame();

- A) I and II only
- B) II and III only
- C) II and IV only
- D) I and IV only
- E) II, III, and IV only

**Answer:** C

#### 3
A method is intended to move anActor from its current grid to a new grid at the same location. Which sequence of method calls is correct?

- A) Put the actor in the new grid, then remove it from the old grid.
- B) Remove the actor from the old grid, then put it in the new grid.
- C) removeSelfFromGrid(); followed by putSelfInGrid(newGrid, loc);
- D) Use a while loop to copy the actor's coordinates.
- E) Reassign the grid reference without calling any methods.

**Answer:** C

#### 4
If d1 and d2 are references to the same Date object (aliases), and d2.addYears(1); is called, what happens to the object referenced by d1?

- A) It remains unchanged.
- B) It is also incremented by one year because both variables point to the same memory address.
- C) It becomes null.
- D) A Compile-time error occurs due to multiple references.
- E) A new Date object is automatically created for d1.

**Answer:** B

#### 5
Which of the following descriptions accurately identifies the relationship between the variable vehicle and the class Car?

- A) vehicle is an attribute of the Car class.
- B) vehicle is an instance of the Car class.
- C) Car is an instance of the vehicle object.
- D) vehicle is a static method within Car.
- E) Car is a primitive data type stored in vehicle.

**Answer:** B

#### 6
A method timesTwo(int n) is called using an Integer object val that stores the value 10\. What is the result?

- A) A Type mismatch error occurs.
- B) The Integer is autounboxed to 10, the method returns 20, and it is printed.
- C) The method returns 10 because Integer is immutable.
- D) The program throws a NullPointerException.
- E) The method must be changed to timesTwo(Integer n).

**Answer:** B

#### 7
Which is the correct way to construct a WindTurbine object with an initial efficiencyRating of 0.25?

- A) WindTurbine wt = new WindTurbine(0.25);
- B) WindTurbine wt = 0.25;
- C) new WindTurbine wt(0.25);
- D) WindTurbine wt.setEfficiency(0.25);
- E) wt = WindTurbine.new(0.25);

**Answer:** A

#### 8
To create an instance of a Point2D class with coordinates (3.0, 4.0), which statement is required?

- A) Point2D p = (3.0, 4.0);
- B) Point2D p = Point2D(3.0, 4.0);
- C) Point2D p = new Point2D(3.0, 4.0);
- D) new Point2D(3.0, 4.0); (without assignment)
- E) p = new Point2D(); p.x = 3.0; p.y = 4.0;

**Answer:** C

#### 9
A Person object student is initialized with the name "Thomas". What is the most appropriate way to change its name to "Tom"?

- A) student = "Tom";
- B) student.myName = "Tom";
- C) student.getName("Tom");
- D) student.setName("Tom");
- E) Person.setName("Tom");

**Answer:** D

#### 10
Which of the following statements about attributes and instances is true?

- A) A class is an instance of its attributes.
- B) Attributes (data) are stored in variables within an instance of a class.
- C) A reference variable stores the actual data of an object.
- D) Methods are instances of class behaviors.
- E) All attributes must be public static.

**Answer:** B

### Topic 3.7 — Class Variables and Methods

#### 1
Which keyword is used to designate that a variable or method belongs to the **class** rather than an instance?

- A) public
- B) private
- C) static
- D) final
- E) void

**Answer:** C

#### 2
A programmer attempts to overload an average method. Which of the following sets of headers will compile without error in the same class?

- I. average(int, int) and average(int, int)

- II. average(int, int) and average(int, int, int)

- III. average(int, int) and average(double, double)

- A) I only
- B) II only
- C) III only
- D) II and III only
- E) I, II, and III

**Answer:** D

#### 3
Given a class SomeClass with a non-static method getA(), which of the following calls from an external class will compile?

- A) SomeClass.getA();
- B) obj.getA(); (where obj is an instance of SomeClass)
- C) int x = getA(obj);
- D) SomeClass.obj.getA();
- E) new getA();

**Answer:** B

#### 4
Which of the following best describes a **class variable**?

- A) A variable unique to every object.
- B) A variable shared by all instances of the class.
- C) A variable that can only be used in the main method.
- D) A variable that cannot be private.
- E) A local variable inside a constructor.

**Answer:** B

#### 5
If a static method calculateAverage is defined in class MathUtils, how should it be called from another class?

- A) MathUtils mu = new MathUtils(); mu.calculateAverage();
- B) MathUtils.calculateAverage();
- C) calculateAverage();
- D) mu.calculateAverage();
- E) new MathUtils.calculateAverage();

**Answer:** B

#### 6
What is the effect of the final keyword when applied to a class variable?

- A) The variable becomes static.
- B) The variable's value cannot be modified after initialization.
- C) The variable is hidden from subclasses.
- D) The variable must be a String.
- E) The variable can only be used in while loops.

**Answer:** B

#### 7
Which of the following is true about static methods?

- A) They can directly access instance variables.
- B) They cannot access instance variables or instance methods without an object reference.
- C) They are called using the new keyword.
- D) They cannot have parameters.
- E) They must always return a double.

**Answer:** B

#### 8
Consider a class Thing with a static method greet(). If a is an instance of Thing, which call is valid?

- I. a.greet();

- II. Thing.greet();

- A) I only
- B) II only
- C) Both I and II
- D) Neither I nor II
- E) Only if greet() is void.

**Answer:** C

#### 9
A class uses a class variable to keep track of the total number of Student objects created. Where should the incrementing of this variable occur?

- A) In a static method.
- B) In the class constructors.
- C) In the main method.
- D) In a final method.
- E) Inside an if statement in the class header.

**Answer:** B

#### 10
Can a class method call another class method in the same class?

- A) No, static methods are independent.
- B) Yes, by using the method name directly or the class name.
- C) Only if the second method is private.
- D) Only if the call is inside a for loop.
- E) Yes, but only if they have different return types.

**Answer:** B

### Topic 3.8 — Scope and Access

#### 1
Where can a **local variable** be accessed?

- A) Anywhere in the class.
- B) Only within the block of code (like a method or loop) where it is declared.
- C) Only within the constructor.
- D) In any subclass of the current class.
- E) By any external class using the dot operator.

**Answer:** B

#### 2
If a method parameter has the same name as an instance variable, what does the name refer to within that method?

- A) The instance variable.
- B) The parameter (local variable).
- C) Both variables simultaneously.
- D) The compiler will report an error.
- E) The static version of the variable.

**Answer:** B

#### 3
What is the **scope** of a formal parameter?

- A) The entire class.
- B) The method in which it is defined.
- C) Only the line where it is initialized.
- D) The main method.
- E) Global scope.

**Answer:** B

#### 4
Which of the following is true about private access?

- A) Private variables are visible to subclasses.
- B) Private variables and methods are only accessible within the class they are declared.
- C) Private methods cannot have parameters.
- D) Private variables are automatically static.
- E) External classes can access private fields using getters. (Note: They access the data, not the field itself).

**Answer:** B

#### 5
A programmer wants to ensure that a Student object's gpa can be read by other classes but not modified directly. What is the best design?

- A) Make gpa public.
- B) Make gpa private and provide no methods.
- C) Make gpa private and provide a public getter (accessor) method.
- D) Make gpa public and static.
- E) Make gpa private and provide a public setter (mutator) method.

**Answer:** C

#### 6
What happens if you try to declare a local variable as public?

- A) It becomes accessible to all classes.
- B) A compiler error occurs (local variables cannot have access modifiers).
- C) It is treated as an instance variable.
- D) It is only visible to the main method.
- E) It remains local but is shared by all loops.

**Answer:** B

#### 7
Which statement is true about equals and \== for String comparison?

- A) They are identical in all cases.
- B) == checks content, equals checks memory address.
- C) == checks memory address, equals checks character sequence.
- D) equals is only for integers.
- E) == is faster and always preferred.

**Answer:** C

#### 8
In a class hierarchy, can a subclass access the private instance variables of its superclass?

- A) Yes, because it is a child class.
- B) No, private variables are restricted to the declaring class.
- C) Only if the subclass is in the same package.
- D) Only if the variable is also static.
- E) Yes, by using the this keyword.

**Answer:** B

#### 9
A method calculate() is defined inside a class. It calls printResult() which is also in the same class. This is legal because:

- A) Both are in the same scope.
- B) Instance methods can call other instance methods of the same class.
- C) calculate() is automatically static.
- D) printResult() is a constructor.
- E) Java requires all methods to be public.

**Answer:** B

#### 10
A variable declared inside the body of a for loop:

- A) Can be used after the loop ends.
- B) Has a scope limited to that for loop.
- C) Is an instance variable.
- D) Must be static.
- E) Cannot be an int.

**Answer:** B

### Topic 3.9 — this Keyword

#### 1
What does the keyword this refer to?

- A) The superclass of the current object.
- B) The current object instance whose method or constructor is being called.
- C) The static variables of the class.
- D) The first parameter of a method.
- E) The main method.

**Answer:** B

#### 2
When is using this required?

- A) To call any instance method.
- B) To distinguish between an instance variable and a parameter with the same name.
- C) To create a new object.
- D) To access a public static variable.
- E) Inside every String method.

**Answer:** B

#### 3
Consider the following constructor:
```java
public Person(String name) {
this.name = name;
}
```
What is the purpose of this.name?

- A) To create a new local variable.
- B) To assign the value of the parameter name to the instance variable name.
- C) To call the Person constructor recursively.
- D) To make the name static.
- E) To convert the string to an object.

**Answer:** B

#### 4
Can this be used in a static (class) method?

- A) Yes, to access static variables.
- B) No, because static methods are not associated with a specific instance.
- C) Only if the method is public.
- D) Yes, but only in the Math class.
- E) Only if it is passed as a parameter.

**Answer:** B

#### 5
Which of the following is a valid use of this to pass the current object as an argument?

- A) calculate(Person this);
- B) calculate(this);
- C) this.calculate();
- D) calculate(new this);
- E) Person(this);

**Answer:** B

#### 6
Inside a method of class Thing, the call this.talk() is equivalent to:

- A) Thing.talk()
- B) talk()
- C) new talk()
- D) a.talk()
- E) super.talk()

**Answer:** B

#### 7
When this is used in a constructor, it must:

- A) Be the last line.
- B) Refer to the object being instantiated.
- C) Be static.
- D) Return a void value.
- E) Be followed by the new keyword.

**Answer:** B

#### 8
If a method returns this, what is the return type of the method?

- A) void
- B) int
- C) The class type itself (the reference type).
- D) Object
- E) boolean

**Answer:** C

#### 9
In the Date class, a method addYears(int n) modifies the current object. Which statement accurately describes the role of this here?

- A) this is a copy of the date.
- B) this allows the method to access and modify the fields of the specific object that called it.
- C) this prevents other objects from being created.
- D) this makes the method static.
- E) this is used to call the constructor of the Object class.

**Answer:** B

#### 10
Which of the following best represents the use of this to call another constructor in the same class (constructor chaining)?

- A) this.Constructor();
- B) this(parameters);
- C) new this(parameters);
- D) this = new Class(parameters);
- E) call this(parameters);

**Answer:** B
