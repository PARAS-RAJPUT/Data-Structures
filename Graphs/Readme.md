# Graph – Data Structure 📊
📌 Introduction

A Graph is a non-linear data structure consisting of a finite set of vertices (nodes) and edges (connections). Graphs are widely used to model real-world problems like social networks, maps, networks, dependency resolution, etc.

1. Basics of Graphs

-> Definition: A set of vertices V and edges E.

-> Terminology: Vertex, Edge, Degree, Path, Cycle, Connected, Components.

-> Types of Graphs

-> Directed vs Undirected

-> Weighted vs Unweighted

-> Cyclic vs Acyclic

-> Connected vs Disconnected

-> Simple, Multigraph, Pseudograph

-> Complete Graph

-> Bipartite Graph

2. Representation of Graphs

-> Adjacency Matrix

-> Adjacency List

-> Edge List

-> Incidence Matrix

-> Comparison of representations (space & time trade-offs).

3. Graph Traversal

-> Depth First Search (DFS)

-> Breadth First Search (BFS)

-> Applications of traversal: Connected components, cycle detection, bipartite check.

4. Shortest Path Algorithms

-> Dijkstra’s Algorithm (single-source shortest path, non-negative weights)

-> Bellman-Ford Algorithm (handles negative weights)

-> Floyd-Warshall Algorithm (all-pairs shortest paths)

A* Algorithm (heuristic-based search)

5. Minimum Spanning Tree (MST)

-> Kruskal’s Algorithm (Union-Find)

-> Prim’s Algorithm (Greedy with priority queue)

6. Special Graph Algorithms

Topological Sorting (DAGs)

-> Detecting Cycles (DFS, Union-Find)

-> Bipartite Graph Check (BFS/DFS coloring)

-> Strongly Connected Components (SCCs) – Kosaraju’s / Tarjan’s algorithm

-> Bridges and Articulation Points (Tarjan’s algorithm)

7. Eulerian Graphs (Euler’s Theorem) 🌀

-> Eulerian Path: A path that visits every edge exactly once.

-> Eulerian Circuit (Cycle): A cycle that starts and ends at the same vertex while visiting every edge exactly once.

-> Euler’s Conditions (Undirected Graphs):

-> Eulerian Circuit exists if all vertices have even degree and the graph is connected.

-> Eulerian Path (but not Circuit) exists if exactly two vertices have odd degree.

-> Otherwise, no Eulerian Path exists.


** Algorithm:

-> Hierholzer’s Algorithm – Efficient method to construct Eulerian Path/Circuit in O(E) time.


| Algorithm             | Time Complexity  | Space Complexity |
| --------------------- | ---------------- | ---------------- |
| BFS/DFS               | O(V + E)         | O(V)             |
| Dijkstra              | O((V + E) log V) | O(V + E)         |
| Bellman-Ford          | O(V * E)         | O(V)             |
| Floyd-Warshall        | O(V³)            | O(V²)            |
| Kruskal               | O(E log E)       | O(V + E)         |
| Prim’s (PQ)           | O((V + E) log V) | O(V + E)         |
| Hierholzer (Eulerian) | O(E)             | O(E)             |

