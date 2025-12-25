### Topic 4.1 — Ethical and Social Issues Around Data Collection

#### 1
Before a mobile application collects a user's physical location and contact list, which of the following actions best satisfies the ethical principle of **informed consent**? 1
A) Hiding the data collection details inside a long Terms of Service agreement.
B) Pre-checking a consent box and allowing the user to continue automatically.
C) Showing a clear prompt describing specific data types and their purpose, requiring the user to tap "Agree".
D) Collecting the data first and then asking for consent after the user has finished onboarding.
E) Skipping consent entirely because the data are considered “non-sensitive” by the developer. **
**Answer:** C

#### 2
An attendance application only requires a student's name and ID number to function. Which approach is most consistent with **data minimization**? 2
A) Collecting the student's home address and GPA for "future analytics."
B) Requiring a birth date to verify age for legal compliance regardless of need.
C) Requiring a mandatory photo upload for profile personalization.
D) Storing only the name and ID; leaving all other fields optional and off by default.
E) Denying access to the app unless a verified phone number is provided. **
**Answer:** D

#### 3
Why might a hiring algorithm that uses a data set of past successful employees produce **biased predictions**? 3
A) Old data sets are always too small to be statistically significant.
B) Past human decisions may encode historical biases that the algorithm then repeats.
C) Sorting training data alphabetically removes all inherent bias from the set.
D) Random shuffling of the data set deletes any systemic bias.
E) Bias in programs only stems from incorrect Java code, never from data. **
**Answer:** B

#### 4
What is the best immediate mitigation after detecting unauthorized access to a database containing student records? 4
A) Delete all existing backups to prevent further exposure.
B) Publicly release all records to ensure maximum transparency.
C) Rotate all credentials, lock down access points, and review audit logs.
D) Disable all encryption protocols to simplify the forensic investigation.
E) Ignore the breach unless it is confirmed that grades were specifically changed. **
**Answer:** C

#### 5
A fitness tracking app shares raw heart-rate data with third-party advertisers. What is the primary **ethical issue**? 5
A) The data are too noisy to be useful for any commercial purpose.
B) Heart-rate data are already anonymized by default by the sensor.
C) Secondary use of sensitive health data without explicit consent violates user expectations.
D) Heart-rate data are not considered Personally Identifiable Information (PII).
E) Advertisers are legally required to aggregate all data safely before use. **
**Answer:** C

#### 6
A company's policy states that server logs are deleted after 30 days, but a developer keeps them for a year. What is the main risk? 6
A) No risk exists if the servers have enough storage capacity.
B) It violates the retention policy and expands the impact surface of a potential breach.
C) It only affects system performance and has no impact on user privacy.
D) It improves model accuracy so it is an acceptable trade-off.
E) Disk encryption removes all ethical risks associated with data retention. **
**Answer:** B

#### 7
Why can simply "removing names" from a data set (de-identification) sometimes fail to protect user identity? 7
A) The resulting file size stays too large for secure transmission.
B) Quasi-identifiers like age and zip code can be linked to other public sets to re-identify individuals.
C) Hashing algorithms always reveal the original identity through a simple reverse search.
D) Only photographic data can be used to re-identify individuals.
E) Data without names are mathematically impossible to link to other sources. **
**Answer:** B

#### 8
A survey application only collects responses from "Premium" users. What type of **bias** does this risk? 8
A) No risk, because premium users represent the most important part of the user base.
B) Sampling bias, as the results skew toward high-activity users, making conclusions invalid for all.
C) Accuracy bias, because fewer samples are more accurate.
D) No bias occurs as long as the questions are written objectively.
E) Bias only occurs in offline physical data sets. **
**Answer:** B

#### 9
Which measure is most appropriate for protecting **sensitive data at rest** (e.g., student grades on a disk)? 9
A) Storing the data in plain text to allow for easier debugging.
B) Using weak encryption to ensure no performance loss during access.
C) Implementing strict access controls and encrypting the physical disk or files.
D) Relying solely on a network firewall to prevent access to the storage device.
E) Making multiple copies on personal devices to ensure data is never lost. **
**Answer:** C

#### 10
If a programmer collects email addresses for "notifications" but later wants to sell them to advertisers, they should: 10
A) Sell the list immediately to maximize company revenue.
B) Send a notification email that doesn't provide a way to opt-out.
C) Obtain explicit opt-in consent for the new purpose or refrain from the secondary use.
D) Proceed because the data were already legally collected.
E) Sell the data as long as it is stored in an encrypted format during transfer. **
**Answer:** C

### Topic 4.2 — Introduction to Using Data Sets

#### 1
Why use an **ArrayList** of Strings rather than an **Array** to read lines from a file of unknown length? 11
A) The get and set methods are more convenient than \[\].
B) The size method provides faster access than the length attribute.
C) An ArrayList can store any data type, whereas arrays only store primitives.
D) The ArrayList will automatically resize itself to avoid out-of-bounds errors.
E) String methods are natively faster in an ArrayList. **
**Answer:** D

#### 2
Which is the best reason to use an **array of int** rather than an **ArrayList of Integer** for long numerical lists? 12
A) Primitive arrays are more memory-efficient and faster to manipulate than wrapper objects.
B) It is easier to code the insertion of new elements into the middle of an array.
C) Deleting elements from the middle is less complex with an array.
D) Arrays allow random access while ArrayLists only allow sequential access.
E) Arrays automatically sort themselves during initialization. **
**Answer:** A

#### 3
What is the time complexity of calculating a sum using a loop that iterates up to a given bound? 13
A) The result is bound, and the time complexity is constant.
B) The execution time is linear (O(n)) relative to the input bound.
C) The result is always zero because the loop never executes.
D) The loop results in an ArithmeticException if the bound is negative.
E) The complexity is quadratic because it uses a nested loop. **
**Answer:** B

#### 4
In a class constructor, which code correctly initializes an array tickList of Ticket objects? 14
A) tickList\[i\] \= new Ticket(getRow(), getSeat(), getPrice());
B) tickList\[i\] \= new Ticket(theRow, theSeat, thePrice);
C) tickList\[i\] \= new tickList(getRow(), getSeat(), getPrice());
D) tickList\[i\] \= new tickList(theRow, theSeat, thePrice);
E) tickList\[i\] \= new tickList(numTicks); **
**Answer:** B

#### 5
Which code segment represents a correct implementation for calculating a sum in a totalPaid method? 14
A) An enhanced for loop that directly accesses the private price field.
B) An enhanced for loop that calls tickList.getPrice().
C) An enhanced for loop that calls t.getPrice() where t is a Ticket object.
D) A standard for loop that iterates through a Transaction object T.
E) A while loop that attempts to access t.price without a getter. **
**Answer:** C

#### 6
A programmer is writing a loop to find the minimum value. How can they avoid skipping the last element? 15
A) Changing the starting index from 1 to 0\.
B) Adjusting the loop body so comparison happens before the index increment.
C) Changing the loop condition to use \<= with the array length.
D) Initializing the minimum variable to 0 before the loop.
E) Using a do-while loop instead of a while loop. **
**Answer:** B

#### 7
Given ArrayList strList, which of the following will cause a compiler error? 16
A) strList.add(ch); (where ch is a character)
B) strList.add("handy andy");
C) strList.add(intOb.toString());
D) strList.add(ch \+ 8); (where the result is a String)
E) strList.add(intOb \+ 8); (where the result is an integer) **
**Answer:** E

#### 8
Given a list containing 6 elements (indices 0 to 5), which statement will **NOT** cause an error? 64
A) list.get(6);
B) list.add(3.4);
C) list.add(6, 9);
D) list.remove(6);
E) list.set(6, 8); **
**Answer:** C

#### 9
A method insert adds an element into a sorted descending list. In which case will it fail? 64
A) It works for all possible values.
B) It fails if the element is already present.
C) It fails if the element is larger than the first item.
D) It fails if the element is smaller than the last item (causing out-of-bounds).
E) It fails if the list is empty. **
**Answer:** D

#### 10
Which is a suitable declaration to keep a list of NUMSALES ticket transactions? 62
A) Transaction\[\] listOfSales \= new Transaction\[NUMSALES\];
B) Transaction\[\] listOfSales \= new Ticket\[NUMSALES\];
C) Ticket\[\] listOfSales \= new Transaction\[NUMSALES\];
D) Ticket\[\] listOfSales \= new Ticket\[NUMSALES\];
E) Transaction\[\] Ticket \= new listOfSales\[NUMSALES\]; **
**Answer:** A

### Topic 4.3 — Array Creation and Access

#### 1
Which of the following correctly creates an array of 10 integers? 43
A) int a\[\] \= new int\[65\];
B) int\[65\] a \= new int;
C) int a \= new int\[65\];
D) int\[\] a \= new int();
E) int a \= {0, 1, 2, 3, 4, 5, 6, 7, 8, 9}; **
**Answer:** A

#### 2
```java
Given int\[\] arr \= {3, 4, 5, 6};, which expression accesses the **last** element? 44
```
A) arr\[67\]
B) arr\[arr.length\]
C) arr\[arr.length \- 1\]
D) arr.last()
E) arr.get(3) **
**Answer:** C

#### 3
What are the initial values of elements in a new int\[69\] array? 44
A) Undefined random values.
B) null
C) 0
D) 1
E) A runtime exception is thrown. **
**Answer:** C

#### 4
```java
What is the result of executing arr\[arr.length\] \= 7;? 44
```
A) The code will fail to compile.
B) A runtime ArrayIndexOutOfBoundsException is thrown.
C) The array will automatically expand.
D) The assignment is ignored.
E) The first element is overwritten. **
**Answer:** B

#### 5
For an array arr, which is the correct way to retrieve the number of elements? 44
A) arr.size()
B) arr.length()
C) arr.length
D) arr.capacity()
E) arr.getLength() **
**Answer:** C

#### 6
```java
Consider: int\[\] a \= {1, 2, 3}; for (int x : a) { x \= x \* 2; }. What is a after execution? 45
```
A) {2, 4, 6}
B) {1, 2, 3}
C) {1, 4, 9}
D) {2, 2, 2}
E) A compiler error occurs. **
**Answer:** B

#### 7
```java
Consider: int\[\] a \= {1, 2, 3}; int\[\] b \= a; b \= 9;. What is a? 45
```
A) 1
B) 2
C) 3
D) 9
E) It is undefined. **
**Answer:** D

#### 8
```java
Given int\[\] a \= {5, 4, 3};, what is the value of a.length? 45
```
A) 2
B) 3
C) 4
D) 0
E) It depends on the JVM. **
**Answer:** B

#### 9
Which for loop header is most appropriate to assign a value to every position in array of length n? 45
A) for (int i \= 1; i \<= n; i++)
B) for (int i \= 0; i \<= n; i++)
C) for (int i \= 0; i \< n; i++)
D) for (int i \= 1; i \< n; i++)
E) for (int i \= \-1; i \< n; i++) **
**Answer:** C

#### 10
```java
What is the difference between int\[\] b \= a; and int\[\] b \= Arrays.copyOf(a, a.length);? 46
```
A) Both create an identical new array in memory.
B) The first creates an alias; the second creates a separate copy.
C) The first creates a copy; the second creates an alias.
D) Both cause a compiler error for primitive arrays.
E) The second statement automatically doubles the size. **
**Answer:** B

### Topic 4.4 — Array Traversals

#### 1
A while loop finds the index of the **first negative integer** in arr. It works when: 46
A) Always.
B) Never.
C) arr contains at least one negative integer.
D) arr contains only non-negative integers.
E) arr contains only zeros. **
**Answer:** C

#### 2
A loop increments index i **before** accessing arr\[i\] for summation. What happens? 47
A) Correct sum.
B) Skips the last element.
C) Skips the first element.
D) Infinite loop.
E) ArrayIndexOutOfBoundsException. **
**Answer:** E

#### 3
```java
Array arr1 contains {0, 6, 0, 4, 0, 0, 2}. After copying non-zeros to arr2, arr2 is: 47
```
A) {6, 4, 2}
B) {0, 0, 0, 0, 6, 4, 2}
C) {6, 4, 2, 4, 0, 0, 2}
D) {0, 6, 0, 4, 0, 0, 2}
E) {6, 4, 2, 0, 0, 0, 0} **
**Answer:** A

#### 4
In a loop from i \= 2 to k, what is the max number of times the body executes? 47
A) 0
B) 1
C) k \- 1
D) k \- 2
E) k **
**Answer:** C

#### 5
Which line correctly prints each name using for (Address a : list)? 47
A) System.out.println(Address\[i\].getName());
B) System.out.println(list\[i\].getName());
C) System.out.println(a\[i\].getName());
D) System.out.println(a.getName());
E) System.out.println(list.getName()); **
**Answer:** D

#### 6
```java
To print detailed addresses using for (Address addr : list), which is correct? 47 I. System.out.println(addr.name \+ addr.street); (private) II. Calling addr.getXxx() methods. III. Calling System.out.println(addr); (toString overridden).
```
A) I only
B) II only
C) III only
D) II and III only
E) I, II, and III **
**Answer:** D

#### 7
Given allStudents, which prints each name using for (Student student : allStudents)? 47
A) System.out.println(allStudents.getName());
B) System.out.println(student.getName());
C) System.out.println(student.getAddress().getName());
D) System.out.println(allStudents.getAddress().getName());
E) System.out.println(student\[i\].getName()); **
**Answer:** C

#### 8
Which is a correct strategy to locate the Student with the **highest ID**? 48 I. Maintain a max variable during traversal. II. Sort and return the first element. III. Sort and return the last element.
A) I only
B) II only
C) III only
D) I and III only
E) I, II, and III **
**Answer:** E

#### 9
A nested loop iterates j from 1 to 4 and k from 1 to 4\. If j starts at 0, the inner count: 48
A) Stays the same (16).
B) Increases by 1\.
C) Increases by 4\.
D) Doubles.
E) Decreases by 4\. **
**Answer:** C

#### 10
Which loop structure prints the digits 987654321? 48
A) Loop incrementing 1 to 9\.
B) Loop decrementing 9 to 1 inclusive.
C) Loop starting at 10 and ending at 0 exclusive.
D) Both B and C.
E) None of the above. **
**Answer:** D

### Topic 4.5 — Implementing Array Algorithms

#### 1
```java
Which method correctly initializes arr to contain four zeros? 48 I. int\[\] arr \= {0, 0, 0, 0}; II. int\[\] arr \= new int\[67\]; III. Using a for loop to assign 0\.
```
A) I only
B) III only
C) I and III only
D) II and III only
E) I, II, and III **
**Answer:** E

#### 2
Finding the first negative integer index fails if: 49
A) The first element is negative.
B) The last element is negative.
C) The array contains no negative integers (causing out-of-bounds).
D) The array has only one element.
E) The negative integer is zero. **
**Answer:** C

#### 3
What error is caused by incrementing index i **before** accessing arr\[i\]? 49
A) Logic error.
B) ArrayIndexOutOfBoundsException.
C) Syntax error.
D) Infinite loop.
E) Arithmetic exception. **
**Answer:** B

#### 4
```java
"Compression" (moving non-zeros) on {0, 6, 0, 4, 0, 0, 2} produces: 49
```
A) {6, 4, 2}
B) {0, 6, 0, 4, 0, 0, 2}
C) {2, 4, 6}
D) {6, 4, 2, 0, 0, 0, 0}
E) {0, 0, 0, 0, 0, 0, 0} **
**Answer:** A

#### 5
If a loop runs from i \= 2 to k, what is the maximum number of iterations? 49
A) k
B) k \+ 1
C) k \- 1
D) 2k
E) k / 2 **
**Answer:** C

#### 6
```java
A method receives an array {0, 1, 2, 3} and modifies indices 1 and 3\. What is printed? 49
```
A) {0, 1, 2, 3}
B) The modified array (e.g., {0, 2, 2, 4}).
C) Only non-modified elements.
D) A NullPointerException.
E) The string "0 2". **
**Answer:** B

#### 7
Which is a correct strategy for finding the **highest ID**? 49 I. Init max to first element. II. Compare each subsequent element to max. III. Update max when higher value is found.
A) I only
B) II only
C) III only
D) I and II only
E) I, II, and III **
**Answer:** E

#### 8
How many times is the condition evaluated in sum(bound) for 0 to bound-1? 49
A) bound
B) bound \+ 1
C) bound \- 1
D) 2 \* bound
E) 1 **
**Answer:** B

#### 9
Loop A prints $m \\times n$. Loop B prints $m \\times (n-1)$. Which is true? 50
A) B prints more.
B) They print same amount.
C) A prints $m$ times more.
D) A prints $n$ times more.
E) B prints $n$ times more. **
**Answer:** D

#### 10
What is a **precondition** for **Binary Search**? 50
A) Array must be even length.
B) No duplicates.
C) Array must be sorted.
D) Target must be present.
E) Must be String objects. **
**Answer:** C

### Topic 4.6 — Using Text Files

#### 1
Why is an **ArrayList** preferred over an **Array** for reading sequential file lines? 50
A) get and set are more convenient.
B) size is faster than length.
C) ArrayLists contain any object type.
D) ArrayList automatically resizes for long files.
E) String methods are easier. **
**Answer:** D

#### 2
When is a missing division-by-zero test detected while reading file expressions? 51
A) At compile time.
B) During editing.
C) When data is read.
D) During evaluation of the expression.
E) After program finish. **
**Answer:** D

#### 3
What is the most reliable way to count file lines with Scanner? 51
A) while (hasNextLine()) { nextLine(); count++; }
B) hasNextInt() to skip data.
C) sc.length()
D) Read to fixed array first.
E) for loop that runs 100 times. **
**Answer:** A

#### 4
Result of failing to call close() on a Scanner? 52
A) Compiler error.
B) File contents deleted.
C) Resource leak (handle remains occupied).
D) JVM shutdown.
E) No consequence. **
**Answer:** C

#### 5
How to skip a CSV file header? 52
A) Call nextLine() once before the loop.
B) Regular expression filter.
C) Count characters in line 1\. ) Convert to array and delete index 0\.
E) Impossible with Scanner. **
**Answer:** A

#### 6
```java
new File("data/input.txt") reports "File Not Found". Most likely cause? 52
```
A) File too large.
B) Relative path incorrect for current directory.
C) Must end with .java.
D) Java doesn't support subdirectories.
E) Scanner must be created first. **
**Answer:** B

#### 7
Which class is most appropriate for **writing** text line-by-line? 52
A) FileInputStream
B) PrintWriter or FileWriter
C) Scanner
D) Math
E) System.in **
**Answer:** B

#### 8
Exception thrown by new Scanner(new File("missing.txt")) if file doesn't exist? 53
A) IOException
B) FileNotFoundException
C) NullPointerException
D) No exception until read.
E) InputMismatchException **
**Answer:** B

#### 9
Most efficient Scanner method to count **individual word** frequency? 53
A) nextLine()
B) nextInt()
C) next()
D) nextDouble()
E) hasNextBoolean() **
**Answer:** C

#### 10
How does nextLine() handle \\r\\n (Windows) vs \\n (Unix)? 53
A) Programmer must strip \\r.
B) Automatically handles common sequences.
C) Fails if no match.
D) Skips every other line.
E) Requires system property. **
**Answer:** B

### Topic 4.7 — Wrapper Classes

#### 1
Consider d1 \+ d2 \+ d3.doubleValue() \+ d4. What is the type and value if total is 100.0? 54
A) 100.0 (primitive double)
B) "10.050.040.0" (String)
C) 10.020.070.0
D) 100 (int)
E) Compiler error. **
**Answer:** A

#### 2
Passing Integer val \= 10 to a method accepting int results in: 54
A) Compiler error.
B) Autounboxing to 10\.
C) NullPointerException.
D) Returns 10 because Integer is immutable.
E) Must overload for Integer. **
**Answer:** B

#### 3
```java
Given Double y \= 3 / 2.0; y /= 2;, what is y.doubleValue()? 54
```
A) 0.0
B) 0.5
C) 0.75
D) 1.0
E) 1.5 **
**Answer:** C

#### 4
Which expression results in random integer 1 to 10 inclusive? 55
A) (int)(Math.random() \* 10\)
B) (int)(Math.random() \* 11\)
C) (int)(Math.random()) \* 10 \+ 1
D) (int)(Math.random() \* 10\) \+ 1
E) Math.random(1, 10\) **
**Answer:** D

#### 5
Assigning Double to double primitive variable: 55
A) Requires explicit cast.
B) Is illegal.
C) Is legal via **automatic unboxing**.
D) Results in precision loss.
E) Only legal if value is 0\. **
**Answer:** C

#### 6
Best practice to compare two Integer objects a and b both at 128? 55
A) a \== b
B) a.equals(b)
C) a \= b
D) a.intValue() \== b.intValue()
E) Both B and D. **
**Answer:** E

#### 7
Which Integer method is preferred over the constructor for performance? 55
A) parseInt
B) valueOf
C) create
D) intValue
E) toString **
**Answer:** B

#### 8
Difference between parseInt("42") and valueOf("42")? 55
A) First returns primitive int; second returns Integer object.
B) First returns Integer; second returns int.
C) Both return same Integer.
D) Both return same int.
E) First is for hexadecimal only. **
**Answer:** A

#### 9
Correctly round negative double d to nearest integer? 56
A) (int)(d \+ 0.5)
B) (int)(d \- 0.5)
C) Math.abs(d)
D) (int)d
E) Math.random() **
**Answer:** B

#### 10
Why avoid \== for floating-point results like 0.1 \+ 0.2 and 0.3? 56
A) Floating-point numbers are objects.
B) Binary representation precision errors.
C) Type mismatch.
D) \== is only for booleans.
E) ArithmeticException. **
**Answer:** B

### Topic 4.8 — ArrayList Methods

#### 1
Advantage of **ArrayList** over **Array** when reading a file? 56
A) Faster access.
B) Less memory.
C) Automatically resizes.
D) Direct int support.
E) No import needed. **
**Answer:** C

#### 2
Implementation more efficient for high-performance math? 56
A) int\[\]
B) ArrayList
C) ArrayList
D) Object\[\]
E) String\[\] **
**Answer:** A

#### 3
Correct line to print name using for (Address a : list)? 57
A) Address.getName()
B) list.getName()
C) list\[i\].getName()
D) a.getName()
E) a\[i\].getName() **
**Answer:** D

#### 4
Valid ways to print Address addr (toString overridden)? 57 I. addr.name \+ addr.street II. System.out.println(addr) III. System.out.println(addr.toString())
A) I only
B) II only
C) III only
D) I and II only
E) II and III only **
**Answer:** E

#### 5
Given ArrayList allStudents, which prints student's address name? 57
A) student.getName()
B) allStudents.getName()
C) student.getAddress().getName()
D) allStudents.get(i).getName()
E) student\[i\].getName() **
**Answer:** C

#### 6
Strategy for finding **highest ID** in an ArrayList? 57
A) Traverse once and maintain max.
B) Nested loop comparison.
C) Both A and B (A more efficient).
D) getHighest() method.
E) list.remove(0) after sort. **
**Answer:** C

#### 7
True about accessing/modifying an ArrayList? 57
A) Use list\[i\].
B) Use get(i) and set(i, val).
C) get(i) returns size.
D) set(i, val) adds element at end.
E) Only modify by delete and re-add. **
**Answer:** B

#### 8
How to retrieve number of elements? 58
A) length
B) length()
C) size()
D) count()
E) capacity() **
**Answer:** C

#### 9
Return values of add(E e) and remove(int index)? 58
A) void and void
B) boolean and element E
C) int and boolean
D) E and boolean
E) Size and removed element. **
**Answer:** B

#### 10
Method to check if object exists? 58
A) exists(x) (address)
B) contains(x) (equals)
C) find(x) (==)
D) search(x) (sort)
E) has(x) (hashCode) **
**Answer:** B
