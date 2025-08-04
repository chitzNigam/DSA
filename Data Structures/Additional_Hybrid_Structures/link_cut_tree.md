# 🧠 Link-Cut Tree

## 🔍 What is it?
A **Link-Cut Tree** is a dynamic tree data structure that supports linking and cutting subtrees and fast path queries between any two nodes.

## ✅ Key Operations
- `link(x, y)` – Connect node `x` to `y`
- `cut(x)` – Remove the connection between `x` and its parent
- `find_root(x)` – Find the root of the tree containing `x`
- `query_path(x, y)` – Aggregate values along the path from `x` to `y`

## 📚 Use Cases
- Dynamic connectivity in forests
- Euler Tour Trees
- Advanced graph algorithms

## 📝 Notes
- Based on splay trees
- Complex but extremely powerful for dynamic trees
