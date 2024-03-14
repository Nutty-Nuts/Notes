---
Course: CSCC 31
Year: "2"
Semester: 2nd
Part: Midterms
---
# INSTRUCTION ARCHITECTURE
---
-  Instruction Set Architecture or ISA defines the interface between the compilers and the hardware.

> [!tip] Fact
> Historically, the Instruction Set Architecture or ISA was developed **before any of the other levels**

> [!note] 
> Instruction Set Architecture or ISA is commonly referred to as **the architecture** of the machine


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
	- Address Modes are the different ways to interpret Address Fields to find the operands

## Immediate Addressing
> [!tip] Fact
> Immediate Addressing is the simplest way of specifying an operand

> [!success] Advantages
> Does not require extra memory reference to fetch the operand

> [!failure] Disadvantages
> Only constants can be supplied this way

- Immediate Addressing is a type of addressing where the operand is automatically fetched from memory at the same time the instruction itself is fetched. *TLDR; part of the instruction contains the operand itself*

## Direct Addressing
> [!danger] Restriction
> The instruction will always access exactly the same memory location which is why it is used to access global variables
> > [!info] Global Variables 
> > Global Variables are variables whose address is known at compile time

- Direct Addressing is a type of addressing that  specifies an operand in memory by giving its full address

## Register Addressing
- Register Addressing is a type of addressing that specifies a register instead of a memory locations.
	- Most common addressing mode due to the speed of registers

## Register Indirect Addressing
- Register Indirect Addressing is a type of addressing were the operand being specified comes from memory but the address is not directly specified in the instruction
### Pointer

> [!success] Advantages
> Register Indirect Addressing can reference memory without paying the price of having a full memory address in the instruction

- Pointer is an address contained in a register

# INSTRUCTION TYPES
---
## Data Movement Instructions
> [!example]
>  - LOAD is an instruction that moves data from memory to register
> - STORE is an instruction that moves data from register to memory
> - MOVE is an instruction that moves data from register to register

- **Data Movement Instructions** are a type of instructions that moves data from one location to another within the computer

## Dyadic Operations
> [!example]
> - Addition and Subtration
> - Boolean Instruction *(e.g. AND, OR, NOT, XOR, NAND)*

- **Dyadic Operations** are a type of instruction where two operands are combined to produce a result

## Monadic Operations
> [!example] 
> - Shifts move bits left or right and bits shifted past the end are lost
> - Rotates move bits left or right and bits shifted  past the end are moved to the opposite end

- **Monadic Operations** are a type of instruction where it uses one operation to produce a result

## Other Instruction Types

# FLOW OF CONTROL
---
- Flow of Control refers to the sequence in which instructions are executed dynamically during program execution
## Branches
- Branches jump to different instructions during program execution without regard to the program counter
## Procedures
- Procedures is an instruction used to perform some specific tasks and returns control to the caller 
## Co-routines
- Co-routines are procedures that call each other to transfer control
## Traps
- Trap is an automatic procedure call initiated by some condition caused by the program and is usually detected by the hardware of microprogram. *(e.g. overflow, undefined opcode, and etc.)*
	- Are also synchronous
## Interrupts
- Interrupts are changes in flow of control caused not by the running program but by something else, usually related to input and output

## Transparency
- Transparency is where some actions and code run but once finished, returns to the state of the computer before the interrupt occurred