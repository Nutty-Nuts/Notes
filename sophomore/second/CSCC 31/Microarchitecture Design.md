---
Course: CSCC 31
Year: "2"
Semester: 2nd
Part: Preliminary
---
# MICROARCHITECTURE
---
- See [[Introduction to Computer Organization#L1 or Microarchitecture|Microarchitecture]]
## Data Path
- **Data Path** is the collection of ALUs and Registers
## Path Length
- **Path Length** refers to the number of clock cycles needed to execute a set of operations
## Speed and Cost Trade-Offs
- **Speed and Cost Trade-offs** is where speed is sacrificed for a lower cost or where cost is increased to increase speed.
## Increasing the Speed of Executing
- The three basic approaches of **Increasing Execution Speed** are the following:
	1. Reducing the number of clock cycles needed to execute an instruction
	2. Simplifying the organization so clock cycles can be shorter
	3. Overlapping the execution of instructions
## Real Estate
- **Real Estate** is the are required for a circuit and is the basis of cost in chip design

# IMPROVING PERFORMANCE
---
## Cache Memory
- See [[CSCC 31/Computer Systems#Cache Memory|Cache Memory]]
### Types of Cache Memory
1. **Direct-Mapped Cache**
	- Direct-Mapped Cache is a type of cache where each line only has a single entry that stores a word. *(each line can store only a single word)*
2. **N-Way Set-Associative Cache**
	- N-Way Set-Associative Cache is a type of cache where each line has multiple entries that stores a word. *(each line can store multiple words)*
### Cache Hit and Cache Miss
1. **Cache Hit**
	- Cache Hit is where the data being fetched or requested by the CPU is found in the cache memory
2. **Cache Miss**
	- Cache Miss is where the data being fetched or requested by the CPU is not found in the cache memory
### Least Recently Used
- LRU or Least Recently Used is an algorithm that finds a memory location that was not used recently and discards the memory.

## Branch Prediction
- **Branch Prediction** is a technique used by the processor to predict the outcome of a conditional branch.
### Types of Branch Prediction
1. **Dynamic Branch Prediction**
	- Dynamic Branch Prediction is a form of branch prediction that predicts the outcome of conditional branches through the use of logic. historical information, and complex algorithms.
2. **Static Branch Prediction**
	- Static Branch Prediction is a form of branch prediction that predicts the outcome of conditional branches through fixed predictions and logic.
### Stalled
- **Stalled** is where executions in a pipeline are paused because the fetch unit does not know where to read until later in the pipeline
### Profiling
- **Profiling** is where a program is run and its branch behavior is captured.

## Out-of-Order Execution and Register Renaming
- **Out-of-Order Execution** is where the CPU skips over dependent instructions to execute independent instructions

## Speculative Execution
- **Speculative Execution** is where the computer executes code before knowing what it is used for.