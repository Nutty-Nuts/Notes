# INTRODUCTION
---
## Instruction Level Parallelism
- **Instruction Level Parallelism** is an exploitation at instruction-level to run as much instruction as possible in a short amount of time via pipelines
## Loop-Level Parallelism
- **Loop Level Parallelism** is a form of parallelism concerned with extracting parallel tasks from loops
## Parallel Instruction
- **Parallel Instructions** are instructions that can be executed simultaneously
## Dependent Instructions
- **Dependent Instructions** are instructions that must be executed in order and therefor cannot be executed simultaneously

# DEPENDENCIES AND HAZARDS
---
## Data Dependence
- **Data Dependence** is a type of dependence when an instruction is dependent on a previous instruction
## Name Dependencies
---
- **Name Dependence** is when two instructions use the same register, memory location, or name
### Antidependence
- **Antidependence** is when an instruction writes to a location that another instruction reads
### Output Dependence
- **Output Dependence** is when an instruction writes in the same location at the same time as another instruction

## Control Dependence
- 
## Data Hazards
- **Data Hazards** is when name or data dependence can occur between instructions close enough to overlap during execution 
### Read-After-Write or RAW
- **Read-After-Write** or **RAW** is when instruction b writes an operand before it is written by instruction a in data dependence
### Write-After-Write or WAW
- **Write-After-Write** or **WAW** is when instruction b writes an operand before it is written by instruction a resulting in output dependence
### Write-After-Read or WAR
- **Write-After-Read** or **WAR** is when instruction b writes to a destination before instruction a can read it resulting in antidependence

# BASIC PIPELINES SCHEDULING
---
- **Basic Pipeline Scheduling** is a process where it finds a sequence of unrelated instructions that may overlap in the pipeline and separate them by a distance in clock cycles equal to pipeline latency

# LOOP UNROLLING
---