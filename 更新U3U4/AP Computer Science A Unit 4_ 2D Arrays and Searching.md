根据 **the sources**（特别是 AP CSA 2025 考纲 CED 与 Unit 4 题目集），以下是 **Unit 4: Data Collections** 中 Topic 4.11 至 4.14 的完整练习题集。  
每小节包含 10 道题目，格式严格遵守“选项换行、排版整齐、真题优先”的原则。

### Topic 4.11 — 2D Array Creation and Access

**题目数量：10**

#### 1 (真题改编)

Consider two nested while loops. Loop A is designed to visit every element in an $m \\times n$ table. Loop B is designed to visit elements in a way that prints $m \\times (n-1)$ times. Which of the following is true regarding the execution? 1A) Loop B executes more statements than Loop A.B) Loop A and Loop B execute the same total number of statements.C) **Loop A prints $m$ times more than Loop B.**D) Loop A prints $n$ times more than Loop B.E) Loop B prints $n$ times more than Loop A.  
**Answer:** C

#### 2

How are two-dimensional (2D) arrays stored and represented in the Java language? 2, 3A) As a single continuous block of linear memory.B) **As an array of arrays.**C) As a linked list of object references.D) As a set of String literals organized in a grid.E) As a static class method with row and column parameters.  
**Answer:** B

#### 3

Which of the following correctly declares and initializes a 2D int array with 2 rows and 3 columns? 2, 4A) int\[\]\[\] arr \= {1, 2, 3, 4, 5, 6};B) int\[\]\[\] arr \= { {1, 2}, {3, 4}, {5, 6} };C) **int\[\]\[\] arr \= { {1, 2, 3}, {4, 5, 6} };**D) int\[\]\[\] arr \= new int\[5\]\[6\];E) int\[7\]\[8\] arr \= new int\[\]\[\];  
**Answer:** C

#### 4

In Java, when accessing an element using the syntax arr\[first\]\[second\], what do the indices typically represent according to the AP Java subset? 4, 9A) Both indices represent row positions.B) The first index is the column and the second is the row.C) **The first index is the row and the second is the column.**D) Both indices represent memory offset values.E) They represent the width and height of the grid respectively.  
**Answer:** C

#### 5

Given a 2D array named values, which expression correctly returns the number of **rows** in the array? 9, 10A) values.size()B) values.length()C) **values.length**D) values.rows()E) values.length  
**Answer:** C

#### 6

For a rectangular 2D array named values, which of the following expressions retrieves the number of **columns**? 9, 10A) values.lengthB) **values.length**C) values.size()D) values.cols()E) values.length()  
**Answer:** B

#### 7

What are the default values for the elements of a 2D int array when it is first created using the new keyword? 4, 11A) nullB) 1C) **0**D) \-1E) false  
**Answer:** C

#### 8

Which syntax is used to access an entire **single row** of a 2D array named arr as a 1D array? 10, 11A) arr\[row\]\[col\]B) **arr\[row\]**C) arr.row(index)D) arr.get(row)E) arr{row}  
**Answer:** B

#### 9

What specific exception is thrown if a program attempts to access an element at arr\[arr.length\] in a 2D array? 10, 11A) NullPointerExceptionB) ArithmeticExceptionC) **ArrayIndexOutOfBoundsException**D) IndexOutOfBoundsExceptionE) ClassCastException  
**Answer:** C

#### 10

Which of the following is true about the **size** of a 2D array after it has been initialized? 3, 12A) The number of rows can be increased using the add method.B) **The size is established at creation and cannot be changed.**C) The array automatically doubles in capacity when it becomes full.D) Rows can be added, but columns remain fixed.E) The size is only limited by the number of String objects in memory.  
**Answer:** B

### Topic 4.12 — 2D Array Traversals

**题目数量：10**

#### 1

Which of the following describes a **row-major order** traversal of a 2D array? 12, 13A) Each column is accessed from top to bottom before moving to the next.B) **Each row is accessed from left to right sequentially.**C) Elements are accessed in a random order to ensure data integrity.D) Only the diagonal elements where row index equals column index are accessed.E) Only the last row is accessed in reverse.  
**Answer:** B

#### 2

Which of the following describes a **column-major order** traversal? 13, 14A) Each row is accessed from left to right sequentially.B) **Elements are accessed by going down each column from top to bottom.**C) The array is converted to a 1D ArrayList before processing.D) The indices are used in reverse order starting from the bottom right.E) Only the elements in the middle column are processed.  
**Answer:** B

#### 3 (真题)

In a nested enhanced for loop used to traverse a 2D array int\[\]\[\] arr, what is the required type for the **outer** loop variable? 14, 15A) intB) IntegerC) **int\[\] (a 1D array)**D) ObjectE) boolean  
**Answer:** C

#### 4 (真题)

In a nested enhanced for loop traversing int\[\]\[\] arr, what is the type of the **inner** loop variable? 15, 16A) int\[\]B) **int**C) doubleD) StringE) void  
**Answer:** B

#### 5

During a 2D array traversal using an **enhanced for loop**, what happens if you assign a new value to the loop variable? 15, 16A) The corresponding value in the original 2D array is updated.B) **The value in the original 2D array remains unchanged.**C) A ConcurrentModificationException is thrown.D) An ArrayIndexOutOfBoundsException occurs.E) The traversal switches from row-major to column-major.  
**Answer:** B

#### 6

In a row-major traversal of an $N \\times M$ array, how many times in total will the **inner** loop body execute? 17A) $N$ timesB) $M$ timesC) **$N \\times M$ times**D) $N \+ M$ timesE) 1 time  
**Answer:** C

#### 7

Which loop structure correctly performs a **column-major** traversal of int\[\]\[\] mat? 17, 18A) for (int r=0; r \< mat.length; r++) followed by for (int c=0; c \< mat\[r\].length; c++)B) **for (int c=0; c \< mat.length; c++) followed by for (int r=0; r \< mat.length; r++)**C) for (int\[\] row : mat)D) while (i \< mat.length)E) for (int r=0; r \< mat.length; r++) { process(mat\[r\]); }  
**Answer:** B

#### 8

Given a square 2D array of size $N \\times N$, a nested loop traverses only the elements where the row index $r$ is equal to the column index $c$. How many elements are visited? 19A) $N^2$B) **$N$**C) $N/2$D) $N(N-1)$E) 1  
**Answer:** B

#### 9

A programmer uses a nested loop to traverse a 2D array. The outer loop runs from $0$ to arr.length \- 1 and the inner loop runs from $0$ to arr.length \- 1\. This is an example of: 13A) Binary Search traversal.B) **Row-major traversal.**C) Column-major traversal.D) Recursive decomposition.E) Informal run-time analysis.  
**Answer:** B

#### 10

If an $R \\times C$ 2D array is traversed row by row, and for each element a constant-time operation is performed, what is the informal execution count? 20A) $R \+ C$B) **$R \\times C$**C) $R^C$D) $2(R+C)$E) $R$  
**Answer:** B

### Topic 4.13 — Implementing 2D Array Algorithms

**题目数量：10**

#### 1 (真题 \- Sample MCQ Q17)

Consider the following code segment: 21  
int\[\]\[\] arr2D \= /\* missing initialization \*/;  
int sum \= 0;  
for (int j \= 0; j \< arr2D.length; j++) {  
    sum \+= arr2D\[j\]\[7\];  
}  
Which initialization for arr2D will cause the code to print the value **3**?A) {{0, 0, 1}, {0, 0, 2}, {0, 0, 1}}B) {{0, 1, 2}, {0, 0, 0}, {0, 0, 0}}C) {{0, 0, 0}, {0, 0, 0}, {1, 1, 1}, {0, 0, 0}}D) **{{0, 0, 1, 0}, {0, 0, 1, 0}, {0, 0, 1, 0}}**E) {{1, 1, 1}, {0, 0, 0}}  
**Answer:** D

#### 2 (真题 \- Sample MCQ Q18)

What is the behavior of the following code segment which processes a 2D array arr? 22  
int ans \= 1;  
for (int\[\] row : arr) {  
    for (int value : row) {  
        if (value \> 0\) {  
            ans \= ans \* value;  
        }  
    }  
}  
A) It prints the product of all elements in arr.B) It prints the product of all negative elements in arr.C) **It prints the product of all positive elements in arr.**D) It prints nothing because of a run-time error if zero is present.E) It prints the sum of all elements in the first row.  
**Answer:** C

#### 3 (真题思路 \- FRQ 4\)

The columnWithFewest(String target) method is intended to find the column index with the minimum occurrences of target. If sched has 3 rows and 5 columns and "busy" appears twice in column 1 and four times in all other columns, what does the method return? 23, 24A) 0B) **1**C) 2D) 3E) 4  
**Answer:** B

#### 4 (真题改编)

A square matrix mat is processed by an algorithm that swaps mat\[i\]\[j\] with mat\[SIZE-j-1\]\[SIZE-i-1\]. What is the visual result of this transformation? 25A) Reflection through the major diagonal.B) **Reflection through the minor diagonal.**C) Horizontal flip (symmetry).D) Vertical flip (symmetry).E) No change occurs.  
**Answer:** B

#### 5

A method alter(mat, c) is intended to remove column c by shifting all subsequent columns one position to the left. Which change correctly fixes an implementation that currently does not shift the last column properly? 26A) **Changing the loop bound to j \< mat.length \- 1\.**B) Changing the starting index to j \= 0.C) Reversing the loop to traverse from right to left.D) Using an enhanced for loop for the columns.E) Making the matrix static.  
**Answer:** A

#### 6

The method isThere(mat, 2, 2, "$") is designed to check for symbols. Which condition guarantees the method returns true? 27A) Only the element at \[7\] is "$".B) All elements in both diagonals are "$".C) **All elements in column 2 are "$".**D) The matrix is empty.E) The matrix size is $2 \\times 2$.  
**Answer:** C

#### 7

When implementing an algorithm to find the **maximum value** in a 2D array, what should the max variable be initialized to for a robust result? 28A) 0B) Integer.MAX\_VALUEC) **arr (the first element)**D) The number of rows in the array.E) A random number from the Math class.  
**Answer:** C

#### 8

An algorithm calculates the **average** of all elements in a designated row r. How many elements are used in the division? 29A) mat.lengthB) **mat\[r\].length**C) mat.size()D) rE) $R \\times C$  
**Answer:** B

#### 9

To compute the sum of a specific **column** c in a 2D array, which traversal is most direct? 13A) Row-major order.B) **Column-major order (iterating through rows while keeping column constant).**C) Main diagonal traversal.D) Binary search of the row.E) Creating a copy of the row.  
**Answer:** B

#### 10

In a 2D array algorithm intended to check for **duplicate** elements, what is the most common implementation approach? 29A) A single loop checking the first row.B) **Nested loops comparing each element against all others or using a helper data structure.**C) Sorting the first column only.D) Comparing the first element to the last element.E) Using the Math.abs() method on the length.  
**Answer:** B

### Topic 4.14 — Searching Algorithms

**题目数量：10**

#### 1 (真题)

The decision to choose a particular searching algorithm (such as linear search vs. more complex ones) should be based on which of the following? 30I. Run-time efficiencyII. Size of the data collectionIII. Memory requirementsA) I onlyB) II onlyC) III onlyD) I and II onlyE) **I, II, and III**  
**Answer:** E

#### 2 (真题)

The following code fragment performs a sequential search for a value in array a. Which of the following should replace /\* boolean expression \*/? 30  
int i \= 0;  
while (/\* boolean expression \*/) { i++; }  
A) value \!= a\[i\]B) i \< n && value \== a\[i\]C) value \!= a\[i\] && i \< nD) **i \< n && value \!= a\[i\]**E) i \< n || value \!= a\[i\]  
**Answer:** D

#### 3

A feature of a data set that is required for a **Binary Search** but is NOT necessary for a **Sequential (Linear) Search** is: 30, 31A) Length of the list.B) Type of the data stored.C) **The order of the data (must be sorted).**D) The presence of duplicate values.E) The use of object references instead of primitives.  
**Answer:** C

#### 4

If a key is NOT present in an array a of length N, what happens during the execution of a linear search using while (a\[index\] \!= key) index++;? 30A) The loop returns \-1 automatically.B) The program terminates successfully with a null value.C) **A runtime ArrayIndexOutOfBoundsException occurs.**D) The loop resets to index 0.E) The compiler reports a syntax error.  
**Answer:** C

#### 5

A linear search algorithm can begin searching from: 32A) Only the beginning of the list.B) Only the end of the list.C) **Either end of the array or ArrayList.**D) Only the middle element.E) Only after the list is sorted alphabetically.  
**Answer:** C

#### 6

When applying a linear search to a **2D array** to find a target value, what is the standard procedure? 33A) Search only the first and last rows.B) Search only the main diagonal.C) **Access each row and then apply a linear search to each row.**D) Flatten the 2D array into a 1D ArrayList first.E) Use a binary search on the columns regardless of sorting.  
**Answer:** C

#### 7

An algorithm searches a sorted array for x by comparing every 3rd item to x. This is faster than a standard binary search when: 30A) x is in the middle.B) **x is very close to the beginning of the array.**C) x is not in the array.) The array is very large.E) It is never faster.  
**Answer:** B

#### 8

What is the informal run-time complexity of a linear search in an array of $n$ elements in the **worst-case** (target not found)? 20, 32A) Constant time.B) **Linear time (proportional to $n$).**C) Quadratic time.D) Logarithmic time.E) Exponential time.  
**Answer:** B

#### 9

A search method includes a loop while (v\[index\] \< key). Which of the following should be part of the **precondition** for this method to work? 30A) **v is sorted from smallest to largest.**B) v is sorted from largest to smallest.C) v contains no duplicates.D) key is definitely in v.E) v is a 2D array.  
**Answer:** A

#### 10

Linear search is considered a **standard algorithm** in Unit 4\. It works by: 32A) Repeatedly dividing the list in half.B) **Checking each element in order until the value is found or the end is reached.**C) Swapping the smallest element with the first element.D) Using a recursive merge process.E) Sorting the list and then picking the middle element.  
**Answer:** B  
**Analogy for Unit 4 (4.11–4.14):**Handling **2D Arrays and Searching** is like **finding a specific book in a multi-story library**:

* **Creation (4.11)** is the architecture—deciding how many floors (rows) and how many shelves (columns) per floor you have.  
* **Traversals (4.12)** is your path—do you walk through every room on floor 1 before going to floor 2 (**row-major**), or do you check the first shelf on every floor before checking the second shelf (**column-major**)?  
* **Algorithms (4.13)** are your tasks—calculating the total number of books or finding the floor with the fewest biographies.  
* **Searching (4.14)** is your strategy—checking every single book one by one (**linear search**) until you find the right one.

