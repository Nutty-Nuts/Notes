---
Course: CSCC 13
Year: "2"
Semester: 2nd
Part: Midterms
---
# GREEDY ALGORITHM
---
- Greedy Algorithm is an algorithm that constructs a solution to an optimization problem piece by piece through a sequence of choices that are: feasible, locally optimal, and irrevocable
	- Some problems, a greedy algorithm can produce an optimal solution
	- Most problems, a greedy problem cannot produce an optimal solution but can be useful for quick approximations
## Optimal Solutions using Greedy Algorithm
---
- The problems that a greedy algorithm can produce an optimal solution are the following:
	- Change Making for Normal Coin Denomination
	- Minimum Spanning Tree *(Kruskal's and Prim's MST)*
	- Dijkstra's Single-Source Shortest Paths
	- Simple Scheduling Programs
	- Huffman Codes
### Prim's MST Algorithm
- Prim's MST Algorithm is an algorithm that can create minimum spanning trees by visiting the closest nodes unvisited nodes of the visited nodes
	- The complexity for this algorithm is $O(n^2)$ for weight matrix representation of graph and array implementation of priority queue
	- The complexity for this algorithm is $O(m\; log\; n)$ for adjacency list representation of graph with $n$ vertices and $m$ edges and min-heap implementation of priority queue 
### Kruskal's MST Algorithm
- Kruskal's MST Algorithm is an algorithm that can create minimum spanning trees by growing a tree edge-by-edge starting with the edge with the smallest weight
### Dijkstra's SSSP Algorithm
- Dijkstra's SSSP Algorithm is an algorithm that finds the shortest paths between nodes in a weighted graph
	- The complexity for this algorithm is $O(|V|^2)$ for weight matrix representation of graph and array implementation of priority queue
	- The complexity for this algorithm is $O(|E|\; log\; |V|)$ for adjacency list representation of graph with $n$ vertices and $m$ edges and min-heap implementation of priority queue 

## Approximations using Greedy Algorithm
- The problems that a greedy algorithm can only produce an approximation are the following:
	- Traveling Salesman Problem
	- Knapsack Problem
	- Combinatorial Optimization Problem