---
Course: CSCC 13
Year: "2"
Semester: 2nd
Part: Preliminary
---
# ALGORITHMS
---
- Algorithms are a finite sequence of instructions, each of which has a clear meaning and can be performed with a finite amount of effort in a finite amount of time
- Algorithms are a sequence of computational steps that transform the input into the output

## Correctness of an Algorithm
- An algorithm is correct if it: (1) halts with the correct output, and (2) the algorithms sovles the problem
### Exceptions 
- Incorrect Algorithms can be useful too if its error rate can be controlled 

## Importance of Algorithms

## Algorithm as a Technology

# DESCRIBING ALGORITHMS
---
## Format for Describing Algorithms
- The following is the format for describing algorithms:
```
Title
Input
Output
Body (Pseudocode, Keywords, Indentations, Special Symbols)
```

## Special Symbols in Describing Algorithms
- The following are Special Symbols in Describing Algorithms:

| Symbol  | Meaning                             |
| ------- | ----------------------------------- |
| ←       | assignment of a value to a variable |
| =       | equality                            |
| [   ]   | array indexing                      |
| //      | comments                            |
| ∅       | empty set                           |
| ∀       | universal quantifier                |
| ∃       | existential quantifier              |
| ⌊ ⌋<br> | floor division                      |
| ⌈ ⌉     | ceiling division                    |
| \|  \|  | absolute value                      |
| ∪       | union of sets                       |
| ∩       | intersection of sets                |
| ∈       | element of a set                    |
| ∉       | not an element of a set             |
| ⊂       | proper subset of a set              |
| ⊆       | improper subset of a set            |
| ≤       | less than or equal to               |
| ≥       | greater than or equal to            |
## Example of Describing Algorithms
- The following is a description of the `MaxArrayElemene` algorithm:
```
ALGORITHM: MaxArrayElement
INPUT: Array of A of n integers
OUTPUT: Integer k such that 𝐴[𝑖] = 𝑘, ∃𝑖 ∈ {0,1 … , 𝑛 − 1} and 𝐴[𝑗] ≤ 𝑘, ∀𝑗 ∈ {0,1, … . 𝑛 − 1}

𝑚𝑎𝑥 ← 𝐴[0]
	for 𝑖 ← 1 to 𝑛 − 1
		if 𝐴 𝑖 > 𝑚𝑎𝑥 then
			𝑚𝑎𝑥 ← 𝐴[𝑖]
return 𝑚𝑎𝑥
```
