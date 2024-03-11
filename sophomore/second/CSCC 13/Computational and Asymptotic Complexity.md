---
Course: CSCC 13
Year: "2"
Semester: 2nd
Part: Preliminary
---
---
## Computational Complexity
- Amount of effort to apply an algorithm or the cost of using algorithm.
### Efficiency Criteria
- Time
- Space

## Comparing Algorithms
### Runtime
- Runtime is system-dependent
### Requirements
- Comparisons must be run on the same machine
- Algorithms must be implemented in the same machine
### Issues w/ Uses Realtime Algorithms
- Requires Implementation of Algorithm
- Requires Execution on the Same Machine
- Interruption of Software Features
- Valid Only for the Test Cases

## Logical Units
- Expresses the relationship between the size $n$ and time $t$ to process

Linear Relationship $t_1 = cn_1$
$n_2 = 5n_1$
$t_2 = 5t_2$

Logarithmic Relationship $t_1 = log_2 \, n$


## Asymptotic Complexity
- Any terms that do not substantially change the function's magnitude is eliminated
- Resulting function is only an approximation, but is sufficiently close to the original
### Big-O Notation
- Most common notation to represent Asymptotic Complexity
- f is the actual runtime, g is the approximation
- c is constant/coefficient of g
- N smallest possible inputs
- n is the number of input
- n must be n >= N
- f grows, at most, as fast as g

- existence of c and N, but not how to calculate

### Other
- Big Theta
- Big Omega
- Small o
- Small Omega

## Simplification
- if f(n) is a sum of terms, only the term with the largest growth is kept
- if f(n) is a product of terms, any constants are omitted