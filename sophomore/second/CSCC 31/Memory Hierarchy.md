---
Course: CSCC 31
Year: "2"
Semester: 2nd
Part: Midterms
---
# MEMORY HIERARCHY
---
- Memory Hierarchy is the relationship between the cost and performance of storage media and is used to find the cheapest and fastest storage media.
## Word
- See [[Computer Systems#Words]]
## Block
- Block is a group of words which is identified by some tag
## Principle of Locality
- See [[Computer Systems#Principle of Locality]]

# CACHE
---
## Types of Cache
---
### N-Way Set Associative Cache
- N-Way Set Associative Cache have an $n$ amount of blocks in a set
- See [[Microarchitecture Design#Types of Cache Memory]]
### Direct-Mapped Cache
- Direct-Mapped Cache has only one block per set
- See [[Microarchitecture Design#Types of Cache Memory]]
### Fully Associative Cache
- Fully Associative Cache has only one set

## Writing to Cache
---
### Write-Through
- Write-Through cache updates the item in cache and in the main memory
### Write Back
- Write Back cache only updates the copy in cache and is only written back when it is about to be replaced
### Write Buffer
- Write Buffer holds data to be written to memory which allows the cache to proceed than wait to write data data into memory

## Miss Rate
- Miss Rate is a fraction or percent of cache that results in a miss
## Causes of Miss Rate
---
### Compulsory
- Compulsory is when the block cannot be in cache and must be brought into cache
### Capacity
- Capacity is when the cache cannot contain all the blocks needed at execution
### Conflict
- Conflict is when blocks are not strategically placed to be fully associative
### Coherency
- Coherency is when cache flush occurs in multiprocessor caches

## Hit Time
- Hit Time refers to the time taken until a cache hit
## Miss Penalty
- Miss Penalty refers to the time taken to replace a block
## Average Memory Access Time
- Average Memory Access Time measure performance through the following formula:
$$\textbf{average\; memory\; access\; time} = hit\; time + miss\; rate\; \cdot\; miss\; penalty$$

# BASIC CACHE OPTIMIZATIONS
---
- *Larger Block Sizes* to reduce miss rate
- *Bigger Caches* to reduce miss rate
- *Higher Associativity* to reduce miss rate
- *Multilevel Cache* to reduce miss penalty
- *Priority to Read Misses Over Writes* to reduce miss penalty
- *Avoid Address Translation During Indexing of the Cache* to reduce hit time

# ADVANCED CACHE OPTIMIZATIONS
---
## Reduced Hit Time
---
### Small and Simple L1 Cache 
- Small and Simple L1 Cache limits the size of the L1 Cache and lowers the level of associativity to reduce the hit time 
### Way-Prediction
- Way-Prediction is to predict the way or block within the set of the next cache to reduce hit time

## Increased Cache Bandwidth
---
### Pipeline Cache
- Pipeline Cache is where cache is accessed through the use of a pipeline
- See [[Computer Systems#Pipelining]]
### Non-Blocking Cache
- Non-Blocking Cache is when Out-of-Order Execution supplies cache despite a mmiss
- See [[Microarchitecture Design#Out-of-Order Execution and Register Renaming]]
### Multi-Banked Cache
- Multi-Banked Cache is where independent banks are used rather than monolithic block for simultaneous access

## Reduce Miss Penalty
---
### Critical Word First and Early Restart
- 
### Merging Write Buffers
- See [[#Write Buffer]]

## Reducing Miss Rate
---
### Compiler Optimization
- Compiler Optimizations is where the compiler of a programming language is optimized for efficient and effective placement of data in memory and cache

## Reducing Miss Penalty or Miss Rate via Parallelism
---
### Hardware Prefetching
- Hardware Prefetching is where items are prefetched before the processor requests them
### Compiler-Controlled Prefetch
- Compiler-Controlled Prefetch is when the compiler inserts prefetch instructions to request data before the processor needs it

# MEMORY TECHNOLOGY
---
## Measures
---
###  Access Time
- Access Time is the time between when a read is requested until the desired word arrives
### Cycle Time
- Cycle Time is the minimum time between unrelated requests to memory

## SRAM Technology
### Static Random Access Memory or SRAM 
- Static Random Access Memory or SRAM does not need to be refreshed at every read and uses six transistors per bit to prevent disruption during reads.
	- SRAM is used in Cache Memory
## DRAM Technology
### Dynamic Random Access Memory or DRAM
- Dynamic Random Access Memory or DRAM requires data to be written back after being read or refereshed
## Flash Memory
- Flash Memory is a type of electronically erasable programmable read-only memory that uses transistors to store data.

# DEPENDABILITY IN MEMORY SYSTEMS
---
## Soft Errors
- Soft Errors are errors caused by changes to cell content
## Hard Errors
- Hard Errors are permanent changes in operation of memory cells

## Error Handling and Detection
---
### Parity Bits
- Parity Bits are check digits that are used the detect single errors in memory
- Parity Bits produce aprox. 90,000 errors in three years or one unrecoverable or undetected failure every 17 minutes.
### Error Correcting Codes or ECC
- Error Correcting Codes or ECC are used to detect multiple errors in memory
- ECC produce aprox. 3,500 errors in three years or one unrecoverable or undetected failure every 7.5 hours.
### Chipkill
- Chipkill is a process that distributes data and ECC information to reconstruct data from failing memory chips and multiple errors
- Chipkill produce aprox. 6 errors in three years or one unrecoverable or undetected failure every 2 months