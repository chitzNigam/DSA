# ⚖️ AVL Tree

## 🔍 What is it?
An **AVL Tree** is a self-balancing Binary Search Tree. It maintains the **balance factor**: the height difference between left and right subtrees is at most 1.

## ✅ Key Operations
- `insert(x)` with rotations
- `delete(x)` with rotations
- `search(x)`
- `inorderTraversal()`

## 📚 Use Cases
- Databases requiring guaranteed log-time operations
- Memory indexing

## 📝 Notes
- Ensures O(log n) height
- Uses left/right/left-right/right-left rotations to maintain balance
