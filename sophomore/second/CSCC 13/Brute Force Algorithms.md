---
Course: CSCC 13
Year: "2"
Semester: 2nd
Part: Midterms
---
# BRUTE FORCE ALGORITHMS
--- 
- Brute Force Algorithms are algorithms with a straightforward approach, usually based directly on the problem's statement and definitions of the concepts involved.
## Examples of Brute Force Algorithms
---
- Examples of Brute Force Algorithms are as follows:
	- Selection Sort
	- String Matching
	- Traveling Salesman Problem
	- Knapsack Problem
	- Assignment Problem
### Selection Sort
- The algorithm description of Selection Sort is the following:
```java
ALGORITHM: SelectionSort(A[0..n-1])
INPUT: An array A[0..n-1] of orderable elements
OUTPUT: A[0..n-1] sorted in ascending order

for 𝑖 ← 0 to 𝑛 − 2 do
	𝑚𝑖𝑛 ← 𝑖
	for 𝑗 ← 𝑖 + 1 to 𝑛– 1 do
		if 𝐴[𝑗] < 𝐴[min] 𝑚𝑖𝑛 ← 𝑗
	swap 𝐴[𝑖] and 𝐴[𝑚𝑖𝑛]
```
### String Matching
- The algorithm description of Selection Sort is the following:
```java
ALGORITHM: BruteForceStringMatching(T[0..n-1], P[0...m-1])
INPUT: An array T[0..n-1] of n characters (text), Array P[0..n-1] of m (pattern)
OUTPUT: Index of first character in text if match, -1 if the search fails

for 𝑖 ← 0 to 𝑛– 𝑚 do
	𝑗 ← 0
	while 𝑗 < 𝑚 and 𝑃[𝑗] = 𝑇[𝑖 + 𝑗] do
		𝑗 ← 𝑗 + 1
	if 𝑗 = 𝑚 return 𝑖
return -1
```

## Strengths of Brute Force Algorithms
- The Strengths of Brute Force Algorithms are as follows:
	- Wide Applicability
	- Simplicity
	- Yields Reasonable Algorithms for Some Important Problems *(matrix multiplication, sorting, searching, string matching)*
## Weaknesses of Brute Force Algorithms
- The Weaknesses of Brute Force Algorithms are as follows:
	- Rarely Yields Efficient Algorithms
	- Some Brute Force Algorithms are Unacceptably Slow
	- Not as Constructive as Some Other Design Techniques
# EXHAUSTIVE SEARCH
---
- Exhaustive Search is a brute force solution to a problem involving searching for an element with a special property *(permutations, combinations, or subsets)*
	- Runs in a realistic amount of time only on very small instances and usually have better alternatives