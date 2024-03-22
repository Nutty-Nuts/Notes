---
Course: CSCC 13
Year: "2"
Semester: 2nd
Part: Preliminary
---
# COMPUTATIONAL COMPLEXITY
---
- **Computational Complexity** is the amount of effort to apply an algorithm and how costly the algorithm is
## Efficiency Criteria
- Computational Complexity has two criteria for efficiency:
	1. Time *(usually more important)*
	2. Space

## Logical Units
- Logical Units are used to express a relationship between the size and time to process

# ASYMPTOTIC COMPLEXITY
---
- **Asymptotic Complexity** is a function that is an approximation of the computational complexity of an algorithm
	- This achieved through the elimination of terms that of a function that do not substantially change the magnitude

## Simplification Rules
- If $f(n)$ is a sum of terms, only the term with the largest growth is kept
- If $f(n)$ is a product of several terms, any constants are omitted

## Asymptotic Complexity Notations
---
### Big-O Notation
- **Big-O Notation** describes the upper bound of the time complexity of an algorithm, in other words, the worst-case time complexity of an algorithm`
	- $g(n)$ is an upper bound on the value of $f(n)$
	- $f$ grows at most as fast as $g$
- *The definition of Big-O Notation are as follows:* given two positive-valued functions $f$ and $g$, $f(n)$ is $O(g(n))$ if there exist positive numbers $c$ and $N$ such that $f(n) \le cg(n)$ for all $n \ge N$
	- $O(g(n) = \{f(n)|\exists c, N\; such\; that\; 0 \le f(n) \le cg(n)\; \forall n \ge N\}$
### Big-Omega Notation
- **Big-Omega Notation** described the lower bound of the time complexity of an algorithm, in other words, the best-case time complexity of an algorithm
- *The mathematical definition of Big-Omega Notation are as follows:*
	- $\Omega(g(n)) = \{f(n)|]\exists c,N\; such\; that\; 0 \le cg(n) \le f(n)\; \forall n \ge N\}$
### Big-Theta Notation
- **Big-Theta Notation** describes the average-case time complexity of an algorithm
- *The definition of Big-Theta Notation are as follows:* $f(n)$ is $\Theta(g(n))$ if and only if $f(n)$ is both $O(g(n))$ and $\Omega(g(n))$
### Small-O Notation
- **Small-O Notation** describes the upper bound of the time complexity of an algorithm, the main difference being that $f(n)$ must always be slower than $g(n)$
- *The mathematical definition of Small-O Notation are as follows:* 
	- $o(g(n)) = \{f(n)|\forall c > 0,\exists N\; such\; that\; 0 \le f(n) < cg(n)\; \forall n \ge N\}$
### Small Omega
- **Small-Omega Notation** describes the lower bound of the time complexity of an algorithm, the main difference being that $f(n)$ must always be faster than $g(n)$
- *The definition of Small-Omega Notation are as follows:* $f(n)$ is $\omega(g(n))$ if and only if $g(n)$ is $o(f(n))$
# COMPLEXITY CLASSES
---
## Constant
- **Constant** is a complexity class where an algorithm takes a constant amount of time no matter how big the problem is
	- The constant complexity class is represented by $O(1)$
## Logarithmic
- **Logarithmic** is a complexity class where an algorithm typically divides the number of items it must consider by a fixed fraction every step
	- The logarithmic complexity class is represented by $O(lg\; n)$
## Linear
- **Linear** is a complexity class where the algorithm's time is directly proportional to the input size 
	- The linear complexity class is represented by $O(n)$
## Quasilinear
- **Quasilinear** is a complexity class where the algorithm's time increases linearly based on the input size but also has a logarithmic component that is applied on every step or iteration
	- The quasilinear complexity class is represented by $O(n\; lg\; n)$ 
## Polynomial
- **Polynomial** is a complexity class that occurs when multiple nested iterations or loops are used in an algorithm
	- The polynomial complexity class is represented by $O(n^k)$ 
## Exponential
- **Exponential** is a complexity class that grows extremely quickly due to its exponential natures and is only practical for small problems
	- The exponential complexity class is represented by $O(2^n)$
## Factorial
- **Factorial** is a complexity class that occurs when an algorithm is designed to look for the optimal arrangement of the inputs
	- The factorial complexity class is represented by $O(n!)$

# BEST, AVERAGE, AND WORST CASE
---
## Worst Case
- **Worst Case** is when an algorithm requires the maximum number of steps
## Best Case
- **Best Case** is when an algorithm requires the minimum number of steps
## Average Case 
- **Average Case** is where the steps that an algorithm requires falls in between the worst and best cases
- Average Complexity is determined by the following factors:
	- Considering possible inputs to an algorithm
	- Determining the number of steps performed for each input
	- Adding the number of steps for all the inputs
	- Dividing by the number of inputs

# TIME AND SPACE TRADE-OFFS
---
- An algorithm may have an efficient Time Complexity but has an inefficient Space Complexity
- An algorithm may also have an inefficient Time Complexity but has an efficient Space Complexity
