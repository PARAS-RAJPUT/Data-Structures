# TOPOLOGICAL SORT 

Topological Sort is a linear ordering of vertices in a Directed Acyclic Graph (DAG) such that for every directed edge
u → v, vertex u appears before vertex v in the ordering.




![kermie-lost-kermit](https://github.com/user-attachments/assets/d0bd3ab4-048c-4701-aa56-5eebfed178f0)





### 1️⃣ Kahn’s Algorithm (BFS-based)

-> Uses in-degree of vertices

-> Processes nodes with in-degree 0

-> Detects cycles efficiently

### 2️⃣ DFS-based Topological Sort

-> Uses depth-first search

-> Pushes nodes to stack after visiting all neighbors

-> Reversing stack gives topological order
