#CC13 
# Introduction
---
## Basic Terms
#### What are some Basic Terms used in Trees?
- Important terminologies of trees are the following:
	1. **Node**
		- Node is an element of a tree
	2. **Arc or Edges** 
		- Arc or Edges is a connection between nodes
	3. **Parent**
		- Parent is the node above a given node connected by an Edge
	4. **Child** 
		- Child is the node below a given node connected by an Edge
	5. **Root** 
		- Root is a node that has no parent
	6. **Leaf** 
		- Leaf is a node that has no children
	7. **Length** 
		- Length is the number of edges in a path
	8. **Height**
		- Height is the maximum level of a node in the tree
	9. **Subtree** 
		- Subtree is any node of a tree that consists of its children and so on
	10. **Visiting** 
		- Visiting is when program control arrives at the node
	11. **Traversing** 
		- Traversing is to visit all nodes in some specified order
	12. **Level** 
		- Level refers to how many generations the node is from the root
	13. **Keys** 
		- Keys are values used to search for the item or perform other operations on it
# Types of Trees
---
## Binary Tree
#### What is a Binary Tree?
- Binary Tree is a type of tree where each node can only have a maximum of 2 children.
## Complete Binary Tree
#### What is a Complete Binary Tree?
- Complete Binary Tree is a type of tree where each node can only have a maximum of 2 children, have all levels filled except for the last level, and are filled from left to right.

> [!info] Detailed Definition
> A **Complete Binary Tree** is defined as:
> 1. Root is at the 1st Level and its Children are at the proceeding Level
> 2. All Nodes except the Leaves have at least 2 Non-Null Children
> 3. All Leaves or End-Nodes are the same Level
> 4. All Leaves must be filled from Left-to-Right

> [!faq] Maximum Number of Nodes
> The formula of Maximum Number of Nodes in a Complete Binary Tree is:
> ---
> $$\Large{N = 2^{(h + 1) -1}}$$
> $\large{let\; N\; be\; max\; no.\; of\; nodes}$
> $\large{let\; h\; be\; height}$

> [!faq] Maximum Number of Nodes at a Level
> The formula of Maximum Number of Nodes in a Complete Binary Tree is:
> ---
> $$\Large{N = 2^{l}}$$
> $\large{let\; N\; be\; max\; no.\; of\; nodes}$
> $\large{let\; h\; be\; height}$

 
## Binary Search Trees
#### What is a Binary Search Tree?
- Binary Search Tree is a type of tree where each node can only have a maximum of 2 children, and where the left child is less than the given node and the right child is greater than the given node.
