# 🔗 Adjacency List

## 🔍 What is it?
An **Adjacency List** represents a graph as a mapping from each vertex to a list of its neighboring vertices.

## ✅ Key Operations
- `addEdge(u, v)` – Adds an edge between u and v
- `getNeighbors(v)` – Returns all neighbors of vertex v

## 📚 Use Cases
- Efficient representation for sparse graphs
- Standard format for graph traversal (DFS, BFS)

## 📝 Notes
- Space Complexity: O(V + E)
- Typically implemented using hash maps or arrays of lists
