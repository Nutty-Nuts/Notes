#CC13 
# Introduction
---
## Basic Terms
#### What is a Node?
- Node is an element of a tree
#### What is an Arc or Edge?
- Arc or Edges is a connection between nodes
#### What is a Parent?
- Parent is the node above a given node connected by an Edge
#### What is a Child?
- Child is the node below a given node connected by an Edge
#### What is a Root?
- Root is a node that has no parent
#### What is a Leaf?
- Leaf is a node that has no children
#### What is Length?
- Length is the number of edges in a path
#### What is Height?
- Height is the maximum level of a node in the tree
#### What is a Subtree?
- Subtree is any node of a tree that consists of its children and so on
#### What is Visiting?
- Visiting is when program control arrives at the node
#### What is Traversing?
- Traversing is to visit all nodes in some specified order
#### What is a Level?
- Level refers to how many generations the node is from the root
#### What are Keys?
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

> [!tip] Maximum Number of Nodes
> The formula of **Maximum Number of Nodes in a Complete Binary Tree** is:
> ---
> $$\Large{N = 2^{(h + 1)}-1}$$
> $\large{let\; N\; be\; max\; no.\; of\; nodes}$
> $\large{let\; h\; be\; height}$

> [!tip] Maximum Number of Nodes at a Level
> The formula of **Maximum Number of Nodes at a Level** is:
> ---
> $$\Large{N = 2^{l}}$$
> $\large{let\; N\; be\; max\; no.\; of\; nodes\; at\; a\; level}$
> $\large{let\; l\; be\; level}$
## Binary Search Trees
#### What is a Binary Search Tree?
- Binary Search Tree is a type of tree where each node can only have a maximum of 2 children, where the left child is less than the given node and the right child is greater than the given node, and no nodes with the same value.

> [!info] Detailed Definition
> A **Binary Search Tree** is defined as:
> 1. Nodes can only have a maximum of 2 Children
> 2. Left Child's value is less than the Parent
> 3. Right Child's value is greater than the Parent
> 4. Nodes cannot have the same value as other Nodes

# Tree Traversal?
---
#### What is Tree Traversal?
- Tree Traversal is the process of visiting each node in the tree exactly one time
- Tree Traversal can be seen as a way or process of linearizing the nodes of a tree
## Breadth-First Traversal
#### What is Breadth-First Traversal?
- Breadth-First Traversal is traversal technique that traverses through the levels of a tree
- Breadth-First Traversal traverses from left-to-right and top-to-bottom
## Depth-First Traversal - Preorder
#### What is Preorder Traversal?
- Preoder Traversal is a depth-first traversal technique.

> [!info] Detailed Definition
> A **Preoder Traversal** performs the following recursive operation in each node:
> 1. Visit the Node
> 2. Go to the Left Child
> 3. Go to the Right Child
## Depth-First Traversal - Inorder
#### What is Inorder Traversal?
- Inorder Traversal is a depth-first traversal technique.
- Inorder Traversal results in a list of nodes arranged in an ascending order.

> [!info] Detailed Definition
> A **Inorder Traversal** performs the following recursive operation in each node:
> 1. Go to the Left Child
> 2. Visit the Node
> 3. Go to the Right Child
## Depth-First Traversal - Postorder
#### What is Postorder Traversal?
- Postorder Traversal is a depth-first traversal technique.

> [!info] Detailed Definition
> A **Postorder Traversal** performs the following recursive operation in each node:
> 1. Go to the Left Child
> 2. Go to the Right Child
> 3. Visit the Node

# Binary Search Tree Insertion
---
#### How are nodes inserted in a Binary Search Tree?
- Insertion in a Binary Search Tree is performed by the following:

> [!info] Detailed Definition
> **Insertion** in a Binary Search Tree is performed in the following steps:
> 1. Is node greater than the current node? 
> 	- If so, then move to the right node
> 	- If not, then move to the left node
> 2. Repeat until a dead end is reached
> 3. Place the new node on the dead end

# Binary Search Tree Deletion
#### How are nodes deleted when a node has no children?
- Nodes are immediately deleted when it has no children
#### How are nodes deleted when a node has one child?
- Nodes are deleted and its child will take its place
#### How are nodes deleted when a node has 2 children?
- Nodes are deleted by performing the delete-by-merging process

> [!info] Detailed Definition
> **Deletion with 2 Children** in a Binary Search Tree is performed in the following steps:
> 1. Node is deleted 
> 2. Root of the Left Subtree of Node takes the place of Node
> 3. Go to the Rightmost Node of the Left Subtree
> 4. Place the Right Subtree of Node on the Rightmost Node of the Left Subtree

# Balancing Binary Search Trees