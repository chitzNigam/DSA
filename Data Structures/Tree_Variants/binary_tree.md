# 🌳 Binary Tree

## 🔍 What is it?
A **Binary Tree** is a tree data structure where each node has at most **two children**, referred to as the left and right child.

## 🧱 Node Structure (C)
```c
struct Node {
    int data;
    struct Node* left;
    struct Node* right;
};
```

## ✅ Key Operations
- **inorderTraversal()**
- **preorderTraversal()**
- **postorderTraversal()**
- **insert()**
- **delete()**
- **search()**

## 📚 Use Cases
- Expression trees
- Hierarchical structures
- Base for more advanced trees like BSTs and heaps

## 📝 Notes
- Not inherently ordered or balanced
- Order of traversal affects output