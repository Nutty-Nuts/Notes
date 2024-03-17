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
### N-Way Set Associative Cache
- N-Way Set Associative Cache have an $n$ amount of blocks in a set
- See [[Microarchitecture Design#Types of Cache Memory]]
### Direct-Mapped Cache
- Direct-Mapped Cache has only one block per set
- See [[Microarchitecture Design#Types of Cache Memory]]
### Fully Associative Cache
- Fully Associative Cache has only one set

## Writing to Cache
### Write-Through
- Write-Through cache updates the item in cache and in the main memory
### Write Back
- Write Back cache only updates the copy in cache and is only written back when it is about to be replaced
### Write Buffer
- Write Buffer holds data to be written t that allows the cache to proceed than wait to write data data into memory


## Miss Rate

## Causes of Miss Rate
### Compulsory
### Capacity
### Conflict
### Coherency

## Hit Time
## Miss Penalty
## Average Memory Access Time