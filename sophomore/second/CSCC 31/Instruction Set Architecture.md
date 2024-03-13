---
Course: CSCC 31
Year: "2"
Semester: 2nd
Part: Midterms
---
# INSTRUCTION ARCHITECTURE
---
> [!tip] Fact
> Historically, the Instruction Set Architecture or ISA was developed **before any of the other levels**

> [!note] 
> Instruction Set Architecture or ISA is commonly referred to as **the architecture** of the machine

-  Instruction Set Architecture or ISA defines the interface between the compilers and the hardware.

## Properties of Instruction Set Architecture Level
*TODO*
## Defining Document
- Defining Document is the collection of information that defines the Instruction Set Architecture Level
### Normative Sections
- Normative Sections contain the imposed requirements of an Instruction Set Architecture Level
### Informative Sections
- Informative Sections contain information that is used to help the reader but are not a part of the formal definition 

# INSTRUCTION ARCHITECTURE  DESIGN
---
## Backwards Compatibility

> [!note]
> Backwards Compatibility is a **massive consideration** when designing new machines or architectures

- **Backwards Compatibility** is the ability of an architecture to run or use software or hardware from the past.
## Characteristics of a Good ISA
- The Two Primary Factors that makes a good Instruction Set Architecture or ISA are the following:
	1. ISA can be implemented efficiently in current and future technologies which results in cost-effective designs over several generations
	2. ISA should provide a clean target for compiled code

# MEMORY MODELS
---
> [!warning] Review 
> See [[Computer Systems#PRIMARY MEMORY]] for additional information

> [!tip] Fact
> Many Architecture require words to be **aligned on their natural boundaries**
> 
> Some architectures do not have this alignment requirement but this does not necessarily lead to faster processing
> > [!info] Info
> > Reading words at arbitrary addresses requires extra logic on the chip which results in a bigger and more expensive chip

# REGISTERS
---

> [!info] Info
> There are some registers that are **visible at the Instruction Set Architecture Level** or ISA Level that is used to control the execution of the program, hold temporary results, and etc.

## Special-Purpose Registers 
- Special-Purpose Registers are registers with specific functions 
### Flag Registers
- Flag Registers are registers that hold various miscellaneous bits needed by the CPU, the most important of which are Condition Codes.

## General-Purpose Registers
- General-Purpose Registers are registers that hold key local variable and intermediate results of calculations

## Condition Codes

> [!info] Info
> Condition Codes are used in comparison and conditional branch instructions

- Condition Codes are used to reflect the status of the result of the most recent operations and is set on every Arithmetic Logic Unit Cycle or ALU Cycle
- The available conditions codes are as follows:
	1. N, result is negative
	2. Z, result is zero
	3. V, result causes an overflow
	4. C, result caused a carry out of the leftmost bit
	5. A, result caused a carry out of bit 3
	6. P, result had even parity

# ADDRESSING
---
- Addressing is to specifying where the operands of an operation is are located
	- Address Fields should follow a specific format
	- Address Modes are the differennt ways to interpret address fields 

## Immediate Addressing


# INSTRUCTION TYPES
---

# FLOW OF CONTROL
---
