# 🔴⚫ Red-Black Tree

## 🔍 What is it?
A **Red-Black Tree** is a self-balancing BST where each node has a color (red or black) and satisfies specific rules that keep the tree approximately balanced.

## ✅ Key Operations
- `insert(x)` (may trigger recoloring and rotations)
- `delete(x)`
- `search(x)`

## 📚 Use Cases
- STL `map` and `set` in C++
- Java `TreeMap` and `TreeSet`
- Filesystems

## 📝 Notes
- Guaranteed O(log n) time for insert, delete, and search
- Easier to implement than AVL for insert-heavy scenarios
