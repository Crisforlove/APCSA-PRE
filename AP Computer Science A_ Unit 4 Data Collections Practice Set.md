### Topic 4.9 — ArrayList Traversals
#### 1
A client method uses an enhanced for loop to generate a list of names from an Address\[\] list. Which is the correct line of code to print each name? 1
A) System.out.println(Address\[i\].getName());
B) System.out.println(list\[i\].getName());
C) System.out.println(a\[i\].getName());
D) System.out.println(a.getName());
E) System.out.println(list.getName()); **
**Answer:** D

#### 2
```java
Which of the following is a correct way to print a list of addresses using a loop variable addr? 2 I. System.out.println(addr.getName() \+ addr.getStreet()); II. System.out.println(addr.toString()); III. System.out.println(addr);
```
A) I only
B) II only
C) III only
D) I and II only
E) II and III only **
**Answer:** E

#### 3
Given a list allStudents, which code segment correctly prints each student's address name? 2
A) System.out.println(allStudents.getName());
B) System.out.println(student.getName());
C) System.out.println(student.getAddress().getName());
D) System.out.println(allStudents.getAddress().getName());
E) System.out.println(student\[i\].getAddress().getName()); **
**Answer:** C

#### 4
Which strategy could correctly replace the body of a method to locate the Student with the highest idNum? 2 I. Initializing a max variable to the first element and updating during traversal. II. Sorting the list and taking the last element. III. Using a nested loop to compare every ID.
A) I only
B) II only
C) III only
D) I and III only
E) I, II, and III **
**Answer:** E

#### 5
What happens if you attempt to add or remove elements from an ArrayList while traversing it using an **enhanced for loop**? 3
A) The list size is updated correctly without error.
B) The loop terminates immediately.
C) A ConcurrentModificationException is thrown.
D) The elements are added to a temporary buffer.
E) The index is automatically adjusted by the JVM. **
**Answer:** C

#### 6
When **deleting elements** during a traversal of an ArrayList, which technique is necessary to avoid skipping elements? 3
A) Using an enhanced for loop.
B) Traversing from the first element to the last using i++.
C) Traversing from the last element to the first or manually adjusting the index.
D) Calling list.clear() inside the loop.
E) Using a while loop that never increments the index. **
**Answer:** C

#### 7
Which method is used to access all or an ordered sequence of elements in an ArrayList? 4
A) Selection
B) **Traversing**
C) Instantiation
D) Concatenation
E) Casting **
**Answer:** B

#### 8
Accessing an index value outside of the range 0 to size \- 1 in an ArrayList results in: 3
A) ArrayIndexOutOfBoundsException
B) NullPointerException
C) IndexOutOfBoundsException
D) ArithmeticException
E) StringIndexOutOfBoundsException **
**Answer:** C

#### 9
Which statement about a for-each loop variable in an ArrayList traversal is true? 2
A) Assigning a new value to the variable changes the value in the ArrayList.
B) The variable holds a copy of the reference to the element.
C) The variable can be used to modify the ArrayList size.
D) The variable is always an int representing the index.
E) The variable must be declared as static. **
**Answer:** B

#### 10
To safely remove elements while traversing, which Java object provides a remove() method that does not skip elements? 5
A) Scanner
B) File
C) Iterator
D) Integer
E) String **
**Answer:** C

### Topic 4.10 — Implementing ArrayList Algorithms
#### 1
A "compression" algorithm for an ArrayList moves only non-zero elements into a new list. If the original list is \[6-8\], what is the result? 9
A) \[6-8\]
B) \[6-8\]
C) \[6-8\]
D) \[6-8\]
E) \[6-8\] **
**Answer:** A

#### 2
Which of the following is a standard ArrayList algorithm to determine the presence of duplicate elements? 10
A) Sorting and checking the first element.
B) Using a single loop to sum all elements.
C) Using nested traversals or a secondary storage to compare elements.
D) Calling list.size().
E) Using the Math.random() method. **
**Answer:** C

#### 3
To find the **minimum** or **maximum** value in an ArrayList, you should: 10
A) Sort the list and return the middle element.
B) Traverse the list while maintaining a variable that stores the smallest/largest value seen so far.
C) Use the Integer.MAX\_VALUE constant to clear the list.
D) Use a while loop that only checks the last element.
E) Convert the list to a String and count characters. **
**Answer:** B

#### 4
Which method is used to insert an element at a specific position index in an ArrayList, shifting subsequent elements to the right? 11
A) set(index, obj)
B) add(obj)
C) add(index, obj)
D) remove(index)
E) insert(index, obj) **
**Answer:** C

#### 5
A standard algorithm to **reverse** the order of elements in an ArrayList can be implemented by: 10
A) Calling list.size() and adding 1 to each index.
B) Swapping elements from opposite ends of the list until the middle is reached.
C) Replacing all elements with null.
D) Using an enhanced for loop to print elements.
E) Adding a new element to the end of the list. **
**Answer:** B

#### 6
What is the effect of calling list.remove(index)? 11
A) It replaces the element with 0\.
B) It removes the element and moves all elements to the right one position to the left.
C) It increases the size of the ArrayList.
D) It returns true if the element was removed.
E) It throws an ArrayIndexOutOfBoundsException if the index is size. **
**Answer:** B

#### 7
Which algorithm involves accessing all **consecutive pairs** of elements? 10
A) Finding the average.
B) Reversing the list.
C) Checking for specific properties between neighbors (e.g., if the list is sorted).
D) Initializing the list with new ArrayList().
E) Converting an int to an Integer. **
**Answer:** C

#### 8
Some algorithms require multiple ArrayList objects to be traversed **simultaneously**. An example is: 12
A) Summing elements in a single list.
B) Comparing elements at the same index in two different lists.
C) Finding the maximum value in one list.
D) Printing a single string.
E) Counting characters in a word. **
**Answer:** B

#### 9
To compute the **average** of numerical values in an ArrayList, the algorithm must: 10
A) Find the maximum value and divide by 2\. ) Traverse the list to compute the sum, then divide by the total number of elements.
C) Multiply all elements together.
D) Return the value at index 0\.
E) Use the Math.sqrt() method on the list size. **
**Answer:** B

#### 10
The standard algorithm to **shift or rotate** elements left or right typically requires: 10
A) A single if statement.
B) A traversal that moves elements to a new index or uses a temporary variable.
C) Setting the list to null.
D) Calling System.out.println.
E) Using a boolean variable. **
**Answer:** B

### Topic 4.11 — 2D Array Creation and Access
#### 1
Consider two nested while loops. Loop A prints $m \\times n$ times. Loop B prints $m \\times (n-1)$ times. Which is true? 13
A) B prints more than A.
B) A and B print the same amount.
C) A prints $m$ times more than B.
D) A prints $n$ times more than B.
E) B prints $n$ times more than A. **
**Answer:** C

#### 2
How are 2D arrays stored in Java? 14
A) As a single continuous block of memory.
B) As an array of arrays.
C) As a linked list of objects.
D) As a set of String literals.
E) As a static class method. **
**Answer:** B

#### 3
Which of the following correctly declares and initializes a 2D int array with 2 rows and 3 columns? 15
A) int\[\]\[\] arr \= {1, 2, 3, 4, 5, 6};
B) int\[\]\[\] arr \= { {1, 2}, {3, 4}, {5, 6} };
C) int\[\]\[\] arr \= { {1, 2, 3}, {4, 5, 6} };
D) int\[\]\[\] arr \= new int\[16\]\[8\];
E) int\[8\]\[16\] arr \= new int\[\]\[\]; **
**Answer:** C

#### 4
When accessing arr\[first\]\[second\], what do the indices represent? 15
A) Both represent rows.
B) The first is columns, the second is rows.
C) The first is rows, the second is columns.
D) Both represent columns.
E) They represent memory addresses. **
**Answer:** C

#### 5
For a 2D array named values, how do you find the number of **rows**? 17
A) values.size()
B) values.length
C) values.length
D) values.rows()
E) values.length() **
**Answer:** C

#### 6
For a 2D array named values, how do you find the number of **columns** (assuming it is rectangular)? 17
A) values.length
B) values.length
C) values.cols()
D) values.size()
E) values.size() **
**Answer:** B

#### 7
What are the default values for elements in a 2D int array created with new? 15
A) null
B) 1
C) 0
D) \-1
E) false **
**Answer:** C

#### 8
A single row of a 2D array can be accessed using: 17
A) arr\[row\]\[col\]
B) arr\[row\]
C) arr.row(index)
D) arr.get(row)
E) arr{row} **
**Answer:** B

#### 9
What exception is thrown if you access arr\[arr.length\]? 17
A) NullPointerException
B) ArithmeticException
C) ArrayIndexOutOfBoundsException
D) StringIndexOutOfBoundsException
E) ClassCastException **
**Answer:** C

#### 10
The size of a 2D array: 14
A) Can be changed using the add method.
B) Is established at creation and cannot be changed.
C) Automatically doubles when full.
D) Is only limited by the number of String objects.
E) Must always be square (rows \== columns). **
**Answer:** B

### Topic 4.12 — 2D Array Traversals
#### 1
**Row-major order** traversal occurs when: 18
A) Each column is accessed from top to bottom.
B) Each row is accessed from left to right sequentially.
C) Elements are accessed randomly.
D) Only the diagonal elements are accessed.
E) Only the first row is accessed. **
**Answer:** B

#### 2
**Column-major order** traversal occurs when: 18
A) Each row is accessed from left to right.
B) Elements are accessed by going down each column.
C) The array is converted to an ArrayList.
D) The indices are used in reverse order.
E) Only the last row is accessed. **
**Answer:** B

#### 3
In a nested enhanced for loop traversing a 2D array int\[\]\[\] arr, what is the type of the **outer** loop variable? 19
A) int
B) Integer
C) int\[\] (1D array)
D) Object
E) boolean **
**Answer:** C

#### 4
In a nested enhanced for loop traversing a 2D array int\[\]\[\] arr, what is the type of the **inner** loop variable? 19
A) int\[\]
B) int
C) double
D) String
E) void **
**Answer:** B

#### 5
What is the result of assigning a new value to the **enhanced for loop variable** during a 2D array traversal? 19
A) The value in the array is updated.
B) It does not change the value stored in the array.
C) It causes a ConcurrentModificationException.
D) It throws an ArrayIndexOutOfBoundsException.
E) It reverses the traversal order. **
**Answer:** B

#### 6
How many times does the inner loop execute in a row-major traversal of an $N \\times M$ array? 18
A) $N$ times
B) $M$ times
C) $N \\times M$ times
D) 1 time
E) 0 times **
**Answer:** C

#### 7
Which loop structure is best for a column-major traversal of int\[\]\[\] mat? 18
A) for (int r=0; r= r? 20
A) $n$
B) $n^2$
C) $n(n+1) / 2$
D) $n(n-1)$
E) $2n$ **
**Answer:** C

### Topic 4.13 — Implementing 2D Array Algorithms
#### 1
Which algorithm involves finding the sum of all elements in a **designated row**? 21
A) Column-major traversal.
B) Row-major traversal of only one index in the outer loop.
C) Binary search.
D) Sorting the 2D array.
E) Recursive character counting. **
**Answer:** B

#### 2
To determine if **duplicate elements** exist in a subsection of a 2D array, which approach is required? 22
A) Using Math.random().
B) Nested iteration statements comparing elements within that subsection.
C) A single if-else statement.
D) Calling arr.length.
E) Casting the array to a Double. **
**Answer:** B

#### 3
What does the following code segment do? (Assuming a square matrix mat and a swap method). 23
A) Reflects mat through its major diagonal.
B) Reflects mat through its **minor (副) diagonal**.
C) Reflects mat through a horizontal line.
D) Reflects mat through a vertical line.
E) Leaves mat unchanged. **
**Answer:** B

#### 4
The method alter is intended to **remove column c**. Which change will correct a buggy implementation? 24 I. Change the loop limit to mat.length \- 1\. II. Shift elements to the left by assigning mat\[i\]\[j\] \= mat\[i\]\[j+1\]. III. Both of the above are valid steps in the correction.
A) I only
B) II only
C) III only
D) I and II only
E) I, II, and III **
**Answer:** E

#### 5
A method isThere(mat, r, c, target) returns true if a specific condition is met. Which condition guarantees a true result if the logic checks rows/columns? 24
A) Only the target cell matches.
B) All elements in the specified column match.
C) All elements in the specified row match.
D) Both B and C are possible depending on implementation.
E) The matrix must be sorted. **
**Answer:** D

#### 6
Standard 2D algorithms can determine a minimum or maximum value: 21
A) Only for the entire array.
B) Only for the first row.
C) For the entire array OR a designated row/column/subsection.
D) Only if the elements are String objects.
E) Using a single while loop. **
**Answer:** C

#### 7
Which algorithm correctly **reverses the order** of elements in a row? 22
A) Sorting the row.
B) Swapping elements in that row from left and right ends.
C) Replacing the row with the first column.
D) Multiplying all elements by \-1.
E) Casting the row to a boolean. **
**Answer:** B

#### 8
To **shift or rotate** elements in a column up or down, the algorithm must: 22
A) Traverse the rows while keeping the column index constant.
B) Traverse the columns while keeping the row index constant.
C) Use the substring() method.
D) Clear the entire 2D array.
E) Call Math.random(). **
**Answer:** A

#### 9
Determining if **all elements** in a designated subsection have a particular property requires: 21
A) A single comparison.
B) A traversal with a boolean "flag" that remains true only if every element meets the criteria.
C) A NullPointerException.
D) A static factory method.
E) An enhanced for loop that returns false at the first element. (Note: It must check all until failure). **
**Answer:** B

#### 10
Calculating the **average** of a designated column involves: 21
A) Summing the entire matrix and dividing by size.
B) Summing the elements in that column and dividing by the number of rows.
C) Summing the first row.
D) Using Math.pow().
E) Dividing the first element by the last. **
**Answer:** B

### Topic 4.14 — Searching Algorithms
#### 1
The decision to choose a particular searching or sorting algorithm should be based on: 25 I. Run-time efficiency. II. Size of the array. III. Space efficiency.
A) I only
B) II only
C) III only
D) I and II only
E) I, II, and III **
**Answer:** E

#### 2
Which boolean expression should replace the placeholder in a **sequential search**? 25
A) value \!= a\[i\]
B) i \< n && value \== a\[i\]
C) value \!= a\[i\] && i \< n
D) i \< n && value \!= a\[i\]
E) i \< n || value \!= a\[i\] **
**Answer:** D

#### 3
What feature is required for a **binary search** but not necessarily for a sequential search? 25
A) Length of list.
B) Type of data.
C) **Order of data (sorted).**
D) Smallest value.
E) Median value. **
**Answer:** C

#### 4
For which operation is a **sorted array** more efficient than an unsorted one? 25 I. Inserting a new element. II. Searching for a given element. III. Computing the mean.
A) I only
B) II only
C) III only
D) I and II only
E) I, II, and III **
**Answer:** B

#### 5
In what case does a "jump" search algorithm (comparing every third item) use **fewer** comparisons than a binary search? 25
A) Never.
B) When the target is in the middle.
C) When the target is very close to the **beginning** of the array.
D) When the target is very close to the end.
E) When the target is not in the array. **
**Answer:** C

#### 6
If the assertion a \> a\[k\] for all $0 \< k \< N$ is true, what must be true? 25
A) The array is sorted ascending.
B) The array is sorted descending.
C) All values are different.
D) a is the smallest.
E) a is the **largest**. **
**Answer:** E

#### 7
```java
A sequential search implementation while(a\[index\] \!= key) index++; will definitely fail if: 25
```
A) The key is the first element.
B) The key is the last element.
C) The key is **not in the array** (causing an index error).
D) The key equals 0\.
E) The key is an Integer object. **
**Answer:** C

#### 8
If a search method contains while (v\[index\] \< key), what should be added to the **precondition**? 26
A) v is sorted smallest to largest.
B) v is sorted largest to smallest.
C) v is unsorted.
D) The key exists in v.
E) The key occurs only once. **
**Answer:** A

#### 9
Linear search algorithms: 27
A) Must start from the middle.
B) Check each element in order until the desired value is found or all elements are checked.
C) Only work on int arrays.
D) Are more efficient than binary search for large sorted lists.
E) Always take constant time. **
**Answer:** B

#### 10
When applying a linear search to a **2D array**: 28
A) You only need one loop.
B) Each row must be accessed, and then linear search is applied to each row.
C) The array must be sorted in column-major order.
D) It is impossible to find a value.
E) You must use Math.pow(). **
**Answer:** B

### Topic 4.15 — Sorting Algorithms
#### 1
Which sorting algorithm repeatedly selects the smallest element from the unsorted portion and **swaps** it into its correct position? 29
A) Selection Sort
B) Insertion Sort
C) Merge Sort
D) Quick Sort
E) Bubble Sort **
**Answer:** A

#### 2
Which sorting algorithm inserts an element into its correct position in the sorted portion by **shifting** other elements? 29
A) Selection Sort
B) Insertion Sort
C) Merge Sort
D) Binary Search
E) Linear Search **
**Answer:** B

#### 3
```java
What would the array {89, 42, \-3, 13, 109, 70, 2} look like after the **third pass** of a selection sort (sorting high to low)? 30
```
A) {109, 89, 70, 13, 42, \-3, 2}
B) {109, 89, 70, 42, 13, 2, \-3}
C) {109, 89, 70, \-3, 2, 13, 42}
D) {89, 42, 13, \-3, 109, 70, 2}
E) {109, 89, 42, \-3, 13, 70, 2} **
**Answer:** B

#### 4
**Selection sort** and **insertion sort** are categorized as: 29
A) Recursive sorting algorithms.
B) Iterative sorting algorithms.
C) Searching algorithms.
D) Constant time algorithms.
E) Random number generators. **
**Answer:** B

#### 5
A sorting algorithm is considered **stable** if: 30
A) It uses no extra memory.
B) It preserves the relative order of elements with equal values.
C) It always takes $O(n^2)$ time.
D) it can only sort integers.
E) It never throws a NullPointerException. **
**Answer:** B

#### 6
Which algorithm is generally more efficient for sorting **long, randomly ordered** lists in the AP CSA curriculum? 31
A) Selection Sort
B) Insertion Sort
C) Merge Sort
D) Linear Search
E) Binary Search **
**Answer:** C

#### 7
Insertion sort is most efficient when: 30
A) The array is already sorted or nearly sorted.
B) The array is sorted in reverse order.
C) The array is completely random.
D) The array contains only zeros.
E) The array size is over 1 million. **
**Answer:** A

#### 8
Selection sort is preferred over insertion sort when: 32
A) Comparisons are expensive but swaps are cheap.
B) **Swaps are expensive** (as it performs at most $n-1$ swaps).
C) The list is already sorted.
D) You need a recursive solution.
E) The array is an ArrayList. **
**Answer:** B

#### 9
In **Selection Sort**, the number of **comparisons** is always: 29
A) Constant.
B) $O(n)$.
C) $O(n^2)$.
D) $O(\\log n)$.
E) Zero. **
**Answer:** C

#### 10
The "sorted portion" of the list in **Insertion Sort** grows by: 29
A) One element per iteration.
B) Half the list per iteration.
C) Random increments. ) Only if the element is smaller than the mean.
E) Converting the array to a String. **
**Answer:** A

### Topic 4.16 — Recursion
#### 1
Which of the following statements about **recursion** are true? 32 I. Every recursive algorithm can be written iteratively. II. Tail recursion is always used in "divide-and-conquer". III. In a recursive definition, a process is defined in terms of a simpler case of itself.
A) I only
B) III only
C) I and II only
D) I and III only
E) II and III only **
**Answer:** D

#### 2
What is the purpose of a **base case** in a recursive method? 33
A) To make the recursive call.
B) To initialize local variables.
C) To halt the recursion.
D) To double the memory usage.
E) To print the result. **
**Answer:** C

#### 3
What value does the recursive call result(5) return if it calculates $2^n$? 34
A) 64
B) 32
C) 16
D) 8
E) 2 **
**Answer:** B

#### 4
How many total calls (including the initial) are made to evaluate result(n) for $n \> 0$ if each call decreases $n$ by 1? 34
A) 2
B) $2n$
C) $n$
D) $n \+ 1$ (if base case is 0\)
E) $n^2$ **
**Answer:** C

#### 5
If a recursive method stringRecur has **no base case**, what will happen? 34
A) It terminates with 0\.
B) It terminates with null.
C) It works for strings shorter than 15\.
D) It runs until a StackOverflowError occurs.
E) The compiler will fix it. **
**Answer:** D

#### 6
A recursive method that prints a character **after** the recursive call will: 34
A) Print the string normally.
B) Print the string in **reverse order**.
C) Print only the first character.
D) Print nothing.
E) Throw an ArithmeticException. **
**Answer:** B

#### 7
What is stored in each recursive call to keep track of progress? 35
A) A global class variable.
B) Its own set of local variables and parameters.
C) A reference to the Math class.
D) A copy of the entire ArrayList.
E) The memory address of the JVM. **
**Answer:** B

#### 8
Which of the following is a recursive method that calculates the **Greatest Common Divisor (GC
D) **? 34
A) f(6, 8\) returning 2\.
B) mystery(3) returning 10\.
C) sum(n) returning n\!.
D) recur(x) returning the maximum.
E) printString(s) reversing the string. **
**Answer:** A

#### 9
A recursive method for $n\!$ should return: 32
A) n \+ sum(n-1)
B) n \* sum(n-1)
C) sum(n) \* sum(n-1)
D) 1
E) n / sum(n-1) **
**Answer:** B

#### 10
Is writing recursive code required on the AP Computer Science A exam? 35
A) Yes, in the FRQ section.
B) No, it is assessed only through the multiple-choice section (tracing).
C) Only if the question involves 2D arrays.
D) Only for the Math class.
E) Yes, but only for sorting. **
**Answer:** B

### Topic 4.17 — Recursive Searching and Sorting
#### 1
Which recursive sorting algorithm divides an array into smaller subarrays until each has one element and then merges them back in order? 31
A) Selection Sort
B) Insertion Sort
C) **Merge Sort**
D) Binary Search
E) Linear Search **
**Answer:** C

#### 2
**Binary Search** is typically more efficient than Linear Search because: 36
A) It works on unsorted lists.
B) It eliminates half of the remaining elements in each recursive call/iteration.
C) It uses more memory.
D) It is iterative only.
E) It only works on String objects. **
**Answer:** B

#### 3
A recursive method doSomething(3) that calls itself twice per level results in which output sequence? 37
A) 3211211
B) 1121213
C) 1213121
D) 1211213
E) 1123211 **
**Answer:** C

#### 4
To use the **Binary Search** algorithm, the data MUST be: 36
A) Positive integers.
B) In sorted order.
C) Shorter than 100 elements.
D) Stored in a File object.
E) Immutable. **
**Answer:** B

#### 5
What is the result of each step of the **Merge Sort** algorithm? 38
A) Elements are swapped into their final position immediately.
B) The array is repeatedly divided into smaller subarrays until they are single elements.
C) The smallest element is moved to the front.
D) The array is cleared and rebuilt.
E) A NullPointerException occurs. **
**Answer:** B

#### 6
Which change in the recursive method writeWithCommas will fix an implementation that prints incorrectly? 39
A) Interchange the lines that print high digits and low digits.
B) Use Math.random().
C) Change the base case to n \> 1000\.
D) Use a while loop instead.
E) Cast the int to a double. **
**Answer:** A

#### 7
The binary search algorithm can be written: 31
A) Only iteratively.
B) Only recursively.
C) Either iteratively or recursively.
D) Only as a static method.
E) Only in the main method. **
**Answer:** C

#### 8
What is the return value of foo(foo(3) \+ foo(4)) if foo(n) calculates $n\!$? 40
A) 15
B) (15\!)/(2\!)
C) (7\!)\!
D) (3\! \+ 4\!)\!
E) 120 **
**Answer:** D

#### 9
Recursion can be used to traverse which data collections? 41
A) String objects
B) Array objects
C) ArrayList objects
D) All of the above
E) None of the above **
**Answer:** D

#### 10
In a recursive binary search, if the target is **not found**: 36
A) The program crashes.
B) The method returns \-1 (or a similar indicator) once the search interval is empty.
C) The method enters an infinite loop.
D) The array is automatically sorted.
E) A FileNotFoundException is thrown. **
**Answer:** B
