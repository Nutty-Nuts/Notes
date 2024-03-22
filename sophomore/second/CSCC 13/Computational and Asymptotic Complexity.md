---
Course: CSCC 13
Year: "2"
Semester: 2nd
Part: Preliminary
---
# COMPUTATIONAL COMPLEXITY
---
- Computational Complexity is the amount of effort to apply an algorithm and how costly the algorithm is
## Efficiency Criteria
- Computational Complexity has two criteria for efficiency:
	1. Time *(usually more important)*
	2. Space

## Logical Units
- Logical Units are used to express a relationship between the size and time to process

# ASYMPTOTIC COMPLEXITY
---
- Asymptotic Complexity is a function that is an approximation of the computational complexity of an algorithm
	- This achieved through the elimination of terms that of a function that do not substantially change the magnitude

## Simplification Rules
- If $f(n)$ is a sum of terms, only the term with the largest growth is kept
- If $f(n)$ is a product of several terms, any constants are omitted

## Asymptotic Complexity Notations
---
### Big-O Notation
- Big-O Notation describes the upper bound of the time complexity of an algorithm, in other words, the worst-case time complexity of an algorithm`
	- $g(n)$ is an upper bound on the value of $f(n)$
	- $f$ grows at most as fast as $g$
- The definition of Big-O Notation are as follows: given two positive-valued functions $f$ and $g$, $f(n)$ is $O(g(n))$ if there exist positive numbers $c$ and $N$ such that $f(n) \le cg(n)$ for all $n \ge N$
	- $O(g(n) = \{f(n)|\exists c, N\; such\; that\; 0 \le f(n) \le cg(n)\; \forall n \ge N\}$
### Big-Omega Notation
- Big-Omega Notation described the lower bound of the time complexity of an algorithm, in other words, the best-case time complexity of an algorithm
- The mathematical definition of Big-Omega Notation are as follows:
	- $\Omega(g(n)) = \{f(n)|]\exists c,N\; such\; that\; 0 \le cg(n) \le f(n)\; \forall n \ge N\}$
### Big-Theta Notation
- Big-Theta Notation describes the average-case time complexity of an algorithm
- The definition of Big-Theta Notation are as follows: $f(n)$ is $\Theta(g(n))$ if and only if $f(n)$ is both $O(g(n))$ and $\Omega(g(n))$
### Small-O Notation
- Small-O Notation describes the upper bound of the time complexity of an algorithm, the main difference being that $f(n)$ must always be slower than $g(n)$
- The mathematical definition of Small-O Notation are as follows: 
	- $o(g(n)) = \{f(n)|\forall c > 0,\exists N\; such\; that\; 0 \le f(n) < cg(n)\; \forall n \ge N\}$
### Small Omega
- Small-Omega Notation describes the lower bound of the time complexity of an algorithm, the main difference being that $f(n)$ 
# COMPLEXITY CLASSES
---
