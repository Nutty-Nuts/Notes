#CSCC11 
# Predicate
---
#### What is a Predicate?
- Predicate refers to a property that the subject of the statement can have.

> [!tip] Breakdown
> **Ex.** $P(x):$ $x$ is greater than 3
> 
> 1. *"x"* is the subject of the statement
> 2. *"is greater than 3"* is the predicate

> [!success]+ Example
> Let $P(x)$ denote the statement $x\;>\;3$
> 
> 1. $\textbf{P(4):}\;4\;>\;3,$ is true
> 2. $\textbf{P(4):}\;2\;>\;3,$ is false

> [!success]+ Example
> Let $Q(x, y)$ denote the statement $x = y + 3$
> 
> 1. $\textbf{Q(1, 2):}\;1 = 2 + 3,$ is false
> 2. $\textbf{Q(3, 0):}\;3 = 0 + 3,$ is true

# Quantifiers
---
#### What is Quantification?
- Quantification is a way to create a proposition from a propositional function
- Quantification expresses the extent to which a predicate is true over a range of elements
	- Quantifier in Quantification are: all, some, many, none, and few
## Types of Quantification
#### What is Universal Quantification?
- Universal Quantification is where a predicate is true for every element under consideration 
	- Universal Quantifier is represented as $\Large{\forall}$
 
 > [!note]+ Information
 > The **universal quantification** of $P(x)$ is the statement "$P(x)$ for all values of $x$ in the domain"
> 
> | Statement               | When True?                         | When False? |
> | ----------------------- | ---------------------------------- | ----------- |
> | $\large{\forall xP(x)}$ | $\large{P(x)}$ is true for every $x$ | There is an $x$ for which $\large{P(x)}$ is false            |

> [!success]+ Example
> **PROBLEM** What is the truth value of the quantification of $\large{\forall xP(X)}$, where the domain consists of all real numbers?
> 
> Let $P(x)$ be the statement $x + 1  > x$
> 
> **SOLUTION** Because $\large{P(x)}$ is true for all real numbers $x$, the quantification $\large{\forall xP(X)}$ is true
#### What is Existential Quantification?
- Existential Quantification is where one or more element under consideration has a predicate that is true
	- Existential Quantifier is represented as $\Large\exists$

> [!note]+ Information
 > The **existential quantification** of $P(x)$ is the statement "There exists an element $x$ in the domain such that $P(x)$"
> 
> | Statement               | When True?                         | When False? |
> | ----------------------- | ---------------------------------- | ----------- |
> | $\large{\exists xP(x)}$ | There is an $x$ for which $\large{P(x)}$ is false | $\large{P(x)}$ is true for every $x$            |

> [!success]+ Example
> **PROBLEM** What is the truth value of the quantification of $\large{\forall xP(X)}$, where the domain consists of all real numbers?
> 
> Let $P(x)$ be the statement $x > 3$
> 
> **SOLUTION** Because $\large{x > 3}$ is sometimes true, for instance, when $\large{x = 4}$, the existential quantification of $\large{P(x)}$ is $\large{\exists xP(x)},$ is true

## Quantifiers with Restricted Domains
#### What is a Restricted Domain?
- A Restricted Domain is a subset of elements from a larger set of elements; a domain of a domain.

> [!success]+ Example
> $\large{\forall x < 0(x^2 > 0)}$ states that
> - For every real number $x$ with $x < 0,$ we have $x^2 > 0$
> - For every negative real number $x,\; x^2 > 0$
> - The square of a negative number is positive
> - $\large{\forall x(x < 0 \rightarrow x^2 > 0)}$
