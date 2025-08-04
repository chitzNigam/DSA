# 🔗 Disjoint Set (Union-Find)

## 🔍 What is it?
A **Disjoint Set** (Union-Find) keeps track of a partition of elements into disjoint (non-overlapping) sets.

## ✅ Key Operations
- `find(x)` – Finds the representative of the set containing x
- `union(x, y)` – Merges the sets containing x and y

## 📚 Use Cases
- Kruskal’s algorithm for MST
- Network connectivity
- Detecting cycles

## 📝 Notes
- Optimizations:
  - **Path compression**: flattens the structure of the tree
  - **Union by rank**: attaches the smaller tree under the larger
- Time Complexity: O(α(n)) per operation (almost constant time)
