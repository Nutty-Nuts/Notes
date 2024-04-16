#CSCC11 
# Proposition
---
#### What is a proposition?
- **Proposition** is a declarative sentence that is either true or false but cannot be both
##### Evidence or Example
> [!example]
> Florida is a state of the United State of America 
> $x + 1 = 3,\: when\: x = 3$

#### What is a Propositional Variable?
- Propositional Variables or Statement Variables are variables that represents propositions

#### What are the truth values of a proposition?
- The truth value of a proposition is true, denoted by is T, if the proposition is true.
- The truth value of a proposition is false, denoted by is F, if the proposition is false.

# Simple and Compound Proposition
---
## Simple Proposition
#### What is a **Simple Proposition?**
- **Simple Proposition** is a statement that conveys a single idea

> [!example] Negation Example
> $\textbf{p:}$ Today is Friday
### Negation
#### What is Negation?
- Negation forms a new proposition with an opposite truth value from the original proposition

> [!example] Negation Example
> $\textbf{p:}$ Today is Friday
> $\pmb{\neg} \textbf{p:}$ Today is **not** Friday

## Compound Proposition
#### What is a **Compound Proposition?**
- **Compound Proposition** is a statement that conveys a two or more ideas
- The Truth Value of a Compound Proposition depends on the truth values of its simple statements.
### Conjunction
#### What is a **Conjunction?**
- **Conjunction** is a compound proposition whose truth value can only be true if the two propositions are both true, false otherwise.

> [!example] Conjunction Example
> $\textbf{p:}$ I am smart
> $\textbf{q:}$ You are handsome
> 
> $\textbf{p} \land \textbf{q}:$ I am smart **and** you are handsome

### Inclusive Disjunction
#### What is an **Inclusive Disjunction?**
- **Inclusive Disjunction** is a compound proposition whose truth values can only be true if at least one of the two proposition is true, false otherwise.

> [!example] Inclusive Disjunction Example
> $\textbf{p:}$ Rebecca's PC has at least 16 GB free hard disk space
> $\textbf{q:}$ The processor in Rebecca's PC runs faster than 1 GHz
> 
> $\textbf{p} \lor \textbf{q}:$ Rebecca's PC has at least 16 GB free hard disk space **or** the processor in Rebecca's PC runs faster than 1 GHz

### Exclusive Disjunction
#### What is an **Exclusive Disjunction?**
- **Exclusive Disjunction** is a compound proposition $p \oplus q$ whose truth values can only be true if only one of the two propositions is true, false otherwise.

> [!example] Exclusive Disjunction Example
> $\textbf{p:}$ This morning I can go to school
> $\textbf{q:}$ This morning I can stay home
> 
> $\textbf{p} \oplus \textbf{q}:$ This morning I can go to school **or** I can stay home

### Conditional Proposition
#### What is Conditional Proposition?
- **Conditional Proposition** is a compound proposition where $p$ is the *hypothesis* and $q$ is the *consequence* 
- **Conditional Proposition** is only false when the $hypothesis$ is false, true otherwise

> [!example] Conditional Proposition Example
> $\textbf{p:}$ Maria learns discrete mathematics
> $\textbf{q:}$ Maria will find a good job
> 
> $\textbf{p} \rightarrow \textbf{q}:$ If Maria learns discrete mathematics, then she will find a good job

### Biconditional Proposition
#### What is a Biconditional Proposition?
- Biconditional Proposition is a compound proposition whose truth value is only true if both propositions have the same truth value, false otherwise 

> [!example] Biconditional Proposition Example
> $\textbf{p:}$ The polygon only has four sides
> $\textbf{q:}$ The polygon is a quadrilateral
> 
> $\textbf{p} \leftrightarrow \textbf{q}:$ The polygon only has four sides if and only if the polygon is a quadrilateral

# Converse, Contrapositive, and Inverse
---
## Converse
#### What is a converse of a conditional proposition?
- Converse of a conditional proposition is where the *hypothesis* swap places with the *consequence*.

> [!example] Converse Example
> $\textbf{conditional\: proposition:} \:$ $p \rightarrow q$
> $\textbf{converse:} \:$ $q \rightarrow p$
## Inverse
#### What is an inverse of a conditional proposition?
- Inverse of a conditional proposition is when negation is applied to both the *hypothesis* and the *consequence*

> [!example] Converse Example
> $\textbf{conditional\: proposition:} \:$ $p \rightarrow q$
> $\textbf{inverse:} \:$ $\neg p \rightarrow \neg q$
## Contrapositive
#### What is a contrapositive of a conditional proposition?
- Contrapositive of a conditional proposition is when a [[#Converse]] and an [[#Inverse]] is applied on a conditional proposition

> [!example] Converse Example
> $\textbf{conditional\: proposition:} \:$ $p \rightarrow q$
> $\textbf{contrapositive:} \:$ $\neg q \rightarrow \neg p$

# Logic and Bit Operations
---
## Bit
#### What is a Bit?
- Bit is a symbol with two possible values *1 or 0* or *true or false*
## Boolean Variable
#### What is a Boolean Variable?
- Boolean Variables is a variables whose value can either be true or false
## Computer Bit Operations
#### What are Computer Bit Operations?
- Computer Bit Operations correspond to the logical connectives. This is achieved through replacing *true or false* with *1 and 0* respectively in the truth table.
## Bit String
#### What is a Bit String?
- Bit String is a sequence of 0 or more bits
### Length
#### What is Length in a Bit String
- Length is the number of bits in the bit string

