---
Course: CSCC 31
Year: "2"
Semester: 2nd
Part: Preliminary
---
# PROCESSORS
---
## Central Processing Unit
- **Central Processing Unit**, aka *The Brain of the Computer*, executes programs stored in the main memory by fetching, decoding, and executing them in a sequential order.
## Arithmetic Logic Unit (ALU)
- **Arithmetic Logic Unit** is a combinational digital circuit that performs arithmetic and bitwise operations on binary numbers.
## Registers
- **Registers** are small but high-speed memory that is located in the CPU and is used to store temporary results and control certain information.
### Types of Registers
1. **Program Counter**
	- Program Counter is a kind of register that points to the next instruction to be fetched for execution
2. **Instruction Register**
	- Instruction Register is a kind of register that holds the instruction being executed.

# CPU ORGANIZATION
---
## Data Path
- **Data Path** is a collection of [[#Registers|Registers]], [[#Arithmetic Logic Unit (ALU)|ALU]], and Buses.
## Data Path Cycle
- **Data Path Cycle** is the process of executing or processing inputs through the ALU and storing the outputs.
## Types of Instructions
1. **Register-Memory**
	- Register-Memory Instructions are instructions that allows data to be fetched from memory into registers
2. **Register-Register**
	- Register-Register Instructions are instructions that allows data to be fetched from a register 
# INSTRUCTION EXECUTION
---
## Fetch-Decode-Execute Cycle
- **Fetch-Decode-Execute Cycle** can be described in the following steps: 
	1. Fetch the next instruction from memory into the instruction register
	2. Change the program counter to point to the following instruction
	3. Determine the type of instruction fetched
	4. IF the instruction uses a word in memory, THEN determine where it is
	5. Fetch the word, IF needed, into a CPU register.
	6. Execute the Instruction
## Reduced Instruction Set Computer (RISC)
- **Reduced Instruction Set Computer** or **RISC** is a computer that executes several simple instructions to perform a complex operation.
## Complex Instruction Set Computer (CISC)
- **Complex Instruction Set Computer** or **CISC** is a computer that executes few complex instructions to perform a complex operation.
# DESIGN PRINCIPLE
---
# PARALLELISM
---
- **Parallelism** is the ability to execute more than one instruction at a time or per clock cycle
## Instruction Level Parallelism
- **Instruction Level Parallelism** is a kind of parallelism that allows a computer to execute multiple instructions concurrently.
### Prefetch Buffer 
- Prefetch Buffer is a collection of registers that store pre-fetched instructions.
### Pipelining
- **Pipelining** is the process of dividing the execution of instructions to many parts where each part is handled by dedicated hardware running in parallel.
- Pipelining has two types which are the following:
	1. Single Pipeline
	2. Dual Pipeline
### Superscalar Architecture
- **Superscalar Architecture** is a type of architecture that allows processors to execute multiple instructions in one clock cycle
### Superscalar Processor
- Superscalar Processor is a processor that has a [[#Superscalar Architecture]], meaning that it can execute more than one instruction per cycle

## Processor Level Parallelism`
- **Instruction Level Parallelism** is a kind of parallelism that makes use of multiple computers or processors to perform or accomplish the same task.
### Multiprocessors
- **Multiprocessors** are computers that uses more than one CPU with each having its own *local memory* and all sharing a *common memory*
### Multicomputers
- **Multicomputers** are systems that use several interconnected computers with each having its own *private memory*.

# PRIMARY MEMORY
---
- **Primary Memory** is a part of the computer where programs and data that are being used by the processor are stored 
## Bit 
- **Bit** or **Binary Digit** is the basic unit of memory and can contain either a 0 or a 1.
## Memory Address
- Memory Address is a reference or identifier use by the computer to identify the location of data in the primary memory.
### Cells
- Cells or Locations are components of the primary memory that store a piece of information in the form of a [[#Byte]].
### Byte
-  Byte is a unit of digital information that consists of 8-bits
### Words
- Words are groups of Bytes

## Byte Ordering
### Big Endian
- Big Endian is type of byte ordering that orders bytes from left-to-right.
### Little Endian
- Big Endian is type of byte ordering that orders bytes from right-to-left.

## Cache Memory
- **Cache Memory** is a small amount of fast memory in the primary memory and is used to store information that is frequently used by the computer.
### Locality Principle
- Locality Principle brings a referenced word and some of its neighbors from memory to the cache for faster access.
### Cache Lines
- Cache Lines are fixed-size blocks that compose the Cache
# SECONDARY MEMORY
---
- Secondary Memory is a part of the computer that stores data and programs for the long term.
## Magnetic Disks
- **Magnetic Disks** are secondary storage devices that uses a disk with a magnetized surface to store data and use magnetic polarities to represent data.
### Track
- Track is a circular sequence of bits, usually 512 bytes, written as the disks completes a rotation.
### Cylinder
- Cylinder is a set of tracks at a give radial position
### Sectors
- Sectors are segments or zones that compose the cylinder

## Solid State Disks
- Solid-State Disks use flash memory rather than disks to store data.
### Wear Levelling
- Wear Levelling is technique where data is stored in cells that have not been used for a while.

## Compact Disc (CD)
- Compact Disc or CD is an optical storage medium that is used to store digital information and uses lasers, pits, and lands to read and write data. *(land to pit is 1, no transition is 0)*
### Pits
- Pits are depressions on the Compact Disc caused by burning via an High-Power Infrared Laser.
### Lands
- Lands are sections of the Compact Disc that are left unburned.
### Types of Compact Disks (CD)
1. **CD ROM or CD-Read Only Memory**
	- CD ROM or CD-Read Only Memory is a type of CD where the data is created along with the CD
2. **CD-Recordable**
	- CD-Recordable is a type of CD that is blank and can be used by users to store data.
3. **CD-Rewritable**
	- CD-Rewritable is a type of CD that can store and delete data.
### DVD
- DVD or Digital Versatile Disk is a medium similar to CD but has smaller pits and tighter spirals which result in larger storage and uses a Red Laser Instead.
### Blu-Ray
- Blu-Ray is a medium similar to CD but uses a Blue Laser instead of a Red Laser which allows it to read smaller pits better.

# Input and Output Devices
---
## Buses
- Buses connect the components of a computer to the CPU via parallel wires.
## Motherboard
- Motherboard is a box or board that contains the CPU, Support Chips, Memory Modules, and I/O Connectors.
## Controller
- Controller is a component that each I/O has that contains all the electronics integrated directly onto the motherboard and controls bus access.
### Direct Memory Access
- Direct Memory Access is the ability of the controller to directly access the memory without the processor.
### Bus Arbiter
- Bus Arbiter is a chip that decides the order of access when the Processor and the I/O Controller want to use the bus at the same time.
### PCI Bus or Peripheral Component Interconnect Bus
- Peripheral Component Interconnect Bus or PCI bus is a bus that is used as an interface to attach hardware devices to a computer 

# INPUT AND OUTPUT
---
## Types of I/O
1. Terminals
2. Mice and Controllers
3. Printers
4. Telecommunications Equipment
5. Camera
6. Character Codes
