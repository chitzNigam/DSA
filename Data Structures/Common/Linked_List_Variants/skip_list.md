# ⏭️ Skip List

## 🔍 What is it?
A **Skip List** is a layered, probabilistic data structure built on linked lists. It uses multiple levels to **"skip" over sections** for faster search, insertion, and deletion.

## 🧱 Node Structure (Conceptual)
Each node contains:
- Value
- Array of forward pointers (to different levels)

## ✅ Key Operations
- **Insert** – Place a node at multiple levels based on probability
- **Delete** – Remove the node and its level pointers
- **Search** – Traverse top-down to reach target in `O(log n)` time

## 📚 Use Cases
- In-memory databases (e.g., Redis)
- Concurrent systems with efficient lookup and modification
- Alternative to balanced binary search trees

## 📝 Notes
- Easier to implement and scale than AVL/Red-Black Trees
- Uses randomness for balance, not rotations
- Good for ordered and concurrent data access