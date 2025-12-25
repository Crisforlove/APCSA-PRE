根据**the sources**，以下是 **Unit 4: Data Collections** 最后三个小节（Topic 4.15–4.17）的完整题目集。这些题目优先采用官方 Sample MCQ 及题库中的高难度计算与代码追踪（Tracing）题，涵盖排序状态、递归栈分析及二分搜索逻辑。

### Topic 4.15 — Sorting Algorithms (排序算法追踪)

**题目数量：10**

#### 1 (官方真题)

Assume that selectionSort (ascending order) has been called with an int\[\] argument initialized with {40, 30, 50, 60, 10, 20}. What will the contents of the array be after **three iterations** of the outer loop (when $j \== 2$)? 1, 2A) {10, 20, 30, 40, 60, 50}B) {10, 20, 30, 60, 40, 50}C) {10, 20, 50, 60, 40, 30}D) {10, 30, 50, 60, 40, 20}E) {10, 20, 30, 40, 50, 60}  
**Answer:** B

#### 2 (真题)

Which of the following should influence the choice of a particular sorting algorithm? 3I. Run-time efficiency of the sortII. Size of the arrayIII. Space efficiency of the algorithmA) I onlyB) II onlyC) III onlyD) I and II onlyE) I, II, and III  
**Answer:** E

#### 3 (高阶追踪)

If an array contains 89 42 \-3 13 109 70 2, what would the array look like after the **third pass** of selectionSort when sorting from **high to low**? 3A) 109 89 70 13 42 \-3 2B) 109 89 70 42 13 2 \-3C) 109 89 70 \-3 2 13 42D) 89 42 13 \-3 109 70 2E) 109 89 42 \-3 13 70 2  
**Answer:** B

#### 4 (算法对比计算)

An array of Integer is to be sorted **biggest to smallest** using insertionSort. If the array contains 1 7 9 5 4 12, what will it look like after the **third pass** of the for loop? 4A) 9 7 1 5 4 12B) 9 7 5 1 4 12C) 12 9 7 1 5 4D) 12 9 7 5 4 1E) 9 7 12 5 4 1  
**Answer:** A

#### 5 (性能分析)

When sorting a long list of integers that is **roughly sorted** in decreasing order (no more than 5% out of order), which is a valid reason to use insertionSort rather than selectionSort? 5I. Fewer comparisons for insertion sort.II. Fewer changes of position for insertion sort.III. Less space required for insertion sort.A) I onlyB) II onlyC) III onlyD) I and II onlyE) I, II, and III  
**Answer:** D

#### 6 (最坏情况计算)

Which of the following represents a **worst-case** situation for the insertionSort algorithm? 6I. A list in correct sorted order.II. A list sorted in reverse order.III. A list in random order.A) I onlyB) II onlyC) III onlyD) I and II onlyE) II and III only  
**Answer:** B

#### 7 (效率对比)

Why is **Merge Sort** generally considered a better algorithm than Insertion Sort for sorting long, randomly ordered lists? 5I. Merge sort requires less code.II. Merge sort requires less storage space.III. Merge sort runs faster.A) I onlyB) II onlyC) III onlyD) I and II onlyE) II and III only  
**Answer:** C

#### 8 (插入排序交换计数)

Which list will require the **greatest number of changes** in position when sorted biggest to smallest with insertionSort? 4A) 5, 1, 2, 3, 4, 7, 6, 9B) 9, 5, 1, 4, 3, 2, 1, 0C) 9, 4, 6, 2, 1, 5, 1, 3D) 9, 6, 9, 5, 6, 7, 2, 0E) 3, 2, 1, 0, 9, 6, 5, 4  
**Answer:** E

#### 9 (选择算法定义)

Selection sort is characterized by which process? 7A) Dividing the array into single elements.B) Inserting elements into a sorted portion by shifting.C) Swapping the smallest remaining element into its final position.D) Using a sentinel to process word lists.E) Recursing until a base case of 0 is reached.  
**Answer:** C

#### 10 (插入排序交换计数)

When sorting a list **biggest to smallest** with insertionSort, which of the following will need the **fewest changes of position**? 4A) 5, 1, 2, 3, 4, 9B) 9, 5, 1, 4, 3, 2C) 9, 4, 2, 5, 1, 3D) 9, 3, 5, 1, 4, 2E) 3, 2, 1, 9, 5, 4  
**Answer:** B

### Topic 4.16 — Recursion (递归逻辑分析)

**题目数量：10**

#### 1 (官方真题)

What is printed as a result of the call mystery(10, 0)? 8  
public static void mystery(int j, int k) {  
    if (j \> k) {  
        mystery(j \- 2, k \+ 2);  
    }  
    System.out.print(j \+ " ");  
}  
A) 10 8 6 4B) 10 8 6C) 6 8 10D) 4 6 8 10E) 2 4 6 8 10  
**Answer:** D

#### 2 (基础概念)

Which of the following statements about recursion are true? 9I. Every recursive algorithm can be written iteratively.II. Tail recursion is always used in "divide-and-conquer" algorithms.III. In a recursive definition, a process is defined in terms of a simpler case of itself.A) I onlyB) III onlyC) I and II onlyD) I and III onlyE) II and III only  
**Answer:** D

#### 3 (代码实现)

Which code segment will enable the method sum to compute $1 \+ 2 \+ ··· \+ n$ correctly for any $n \> 0$? 9A) return n \+ sum(n \- 1); (missing base case)B) if (n \== 0\) return 0; else return n \+ sum(n \- 1);C) if (n \== 1\) return 1; else return n \+ sum(n \- 1);D) Both B and CE) Neither A nor B  
**Answer:** D

#### 4 (终止性分析)

When will method stringRecur terminate without error if it has **no base case** and always calls substring(1)? 9A) Only when length \< 15B) Only when length \>= 15C) Only when an empty string is inputD) For all string inputsE) For no string inputs (Infinite recursion)  
**Answer:** E

#### 5 (计算追踪)

What value does result(5) return if the method is defined as return 2 \* result(n \- 1\) with base case result(0) \= 1? 10A) 64B) 32C) 16D) 8E) 2  
**Answer:** B

#### 6 (调用次数计算)

If $n \> 0$, how many times will result be called to evaluate result(n) (including the initial call) if each call invokes result(n-1)? 10A) 2B) $2n$C) $n+1$D) $n$E) $n^2$  
**Answer:** C (or D depending on if $n=0$ is the final call; following 11 result is $n$)

#### 7 (追踪题)

What value is returned by the call mystery(3, 2, 6\) if it computes an arithmetic sequence? 10A) 20B) 14C) 10D) 8E) 2  
**Answer:** B

#### 8 (GCD 追踪)

Refer to method f(int a, int b). What value is returned by the call f(6, 8\) if it returns f(b, a % b)? 10A) 8B) 4C) 3D) 2E) 1  
**Answer:** D

#### 9 (数组递归分析)

What does method recur do if it returns Math.max(x\[n-1\], recur(x, n-1))? 10A) It finds the largest value in x and leaves x unchanged.B) It finds the smallest value.C) It sorts x in ascending order.D) It sorts x in descending order.E) It returns x.  
**Answer:** A

#### 10 (行为追踪)

Which best describes what printString does if it calls printString(s.substring(1)) **before** System.out.print(s.substring(0, 1))? 10A) It prints string s.B) It prints string s in reverse order.C) It prints only the first character.D) It prints only the first two characters.E) It prints only the last character.  
**Answer:** B

### Topic 4.17 — Recursive Searching and Sorting (综合递归查找)

**题目数量：10**

#### 1 (代码补全)

Which code correctly completes method power to handle negative exponents where $a^{-n} \= 1/a^n$? 12A) (1.0 / base) \* power(base, expo \+ 1)B) (1 / base) \* power(base, expo \- 1)C) base \* power(base, expo \+ 1)D) base \* power(base, expo \- 1)E) (1 / base) \* power(base, expo)  
**Answer:** A

#### 2 (输出追踪)

What would be output following the call doSomething(3) if the method prints n, then recurses n-1 twice? 12A) 3211211B) 1121213C) 1213121D) 1211213E) 1123211  
**Answer:** C

#### 3 (回溯输出)

Which code satisfies the postcondition of writeEven (printing even integers in reverse order of input)? 12A) I only (print then recurse)B) II only (recurse then print)C) III only (if even, recurse, then print)D) I and II onlyE) I, II, and III  
**Answer:** C

#### 4 (递归求和)

What value is returned by the call mystery(3) if it returns n \+ mystery(n-1)? 12A) 12B) 10C) 8D) 6E) 4  
**Answer:** D (If mystery(3) \= 3+2+1+0)

#### 5 (二分搜索追踪)

A binary search for key **27** is performed on {4, 7, 9, 11, 20, 24, 30, 41}. What is the search interval after the **first pass**? 13A) a … a14B) a15 … a16C) a17 … a14D) a18 … a16E) a16 … a14  
**Answer:** C

#### 6 (二分搜索计算)

How many iterations will be required to determine that **27** is **not** in the list above? 13A) 1B) 2C) 3D) 4E) 8  
**Answer:** C

#### 7 (递归调用计数)

For the method call t(6), if t(n) calls t(n-2) \+ t(n-3), how many calls to t will be made total? 19A) 6B) 7C) 11D) 15E) 25  
**Answer:** C

#### 8 (复杂递归追踪)

What will be the value of z after z \= foo(foo(3) \+ foo(4)) if foo(n) returns $n\!$? 19A) (15\!)/(2\!)B) 3\! \+ 4\!C) (7\!)\!D) (3\! \+ 4\!)\!E) 15  
**Answer:** D

#### 9 (二分搜索查找失败)

If a binary search is performed on 30,000 elements, what is the smallest number of iterations that guarantees the key is found or proven absent? 13A) 15B) 30C) 100D) 300E) 3000  
**Answer:** A (因为 $2^{15} \> 30000$)

#### 10 (归并排序定义)

What is the purpose of the merge method in Merge Sort? 5A) Partition the array into two parts and swap pivots.B) Recursively sort the entire array.C) Divide the array into $n$ subarrays.D) Merge two sorted parts into a single sorted array.E) Move elements to a temporary non-sorted array.  
**Answer:** D  
**Analogy for Unit 4 Completion:**Mastering **Sorting and Recursion** is like **organizing a library using magic**:

* **Sorting (4.15)**: Selection sort is like finding the shortest book in a pile and putting it first, over and over. Insertion sort is like taking one book and sliding it into the correct spot in your hands.  
* **Recursion (4.16)**: Is like a **dream within a dream**. Each level has its own reality (variables), and you can only wake up (return) once you reach the base level.  
* **Recursive Searching (4.17)**: Binary search is like searching for a word in a dictionary by always jumping to the middle and tearing the wrong half away until only the word remains.

