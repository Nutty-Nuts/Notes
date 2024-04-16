---
Course: CSCC 13
Year: "2"
Semester: 2nd
Part: Midterms
---
# DIVIDE AND CONQUER ALGORITHM
---
- Divide-And-Conquer Algorithms are algorithms that incorporate one of the following design strategies:
	- Divide an instance of a problem into two or more smaller instances
	- Solve smaller instances recursively
	- Obtain solution to original instance by combining these solutions

## General Divide and Conquer Recurrence
- The General Divide and Conquer Recurrence are the following:
	- $T(n) = a\; \cdot \;T(n/b) +f(n)$ where $f(n) = O(n^d), d \ge 0$
### Master Theorem
- The master theorem for the General Divide and Conquer Recurrence are the following:
	- if $a < b^d$, then $T(n) = O(n^d)$
	- if $a = b^d$, then $T(n) = O(n^d\; log\; n)$
	- if $a > b^d$, then $T(n) = O(n^{log_b\; a})$

## Examples of Divide and Conquer Algorithms
- Examples of divide and conquer algorithms are the following:
	- Mergesort
	- Quicksort
	- Binary Tree Traversals
	- Multiplication of Large Integers
	- Closest-Pair Algorithm
	- Convex-Hull Algorithm
	- Binary Search