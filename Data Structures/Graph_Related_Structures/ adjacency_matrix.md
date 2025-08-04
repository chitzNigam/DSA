# 🧮 Adjacency Matrix

## 🔍 What is it?
An **Adjacency Matrix** is a 2D array representation of a graph. Each cell `(i, j)` indicates whether there is an edge from node `i` to `j`.

## ✅ Key Operations
- `addEdge(i, j)` – Sets matrix[i][j] = 1 (or weight for weighted graphs)
- `hasEdge(i, j)` – Checks if an edge exists

## 📚 Use Cases
- Dense graphs
- Fast edge lookups (O(1))

## 📝 Notes
- Space Complexity: O(V²)
- Inefficient for sparse graphs
