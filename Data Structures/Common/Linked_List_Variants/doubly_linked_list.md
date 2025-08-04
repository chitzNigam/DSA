# 🔁 Doubly Linked List

## 🔍 What is it?
A **Doubly Linked List** is a linear structure where each node has:
- A data field
- A pointer to the **next node**
- A pointer to the **previous node**

This allows **bidirectional traversal**, forward and backward.

## 🧱 Node Structure (C)
```c
struct Node {
    int data;
    struct Node* prev;
    struct Node* next;
};
```

## ✅ Key Operations
- **Insert at Beginning** – Add a node before the current head.
- **Insert at End** – Add a node after the tail.
- **Delete Node** – Remove a node by pointer or value.
- **Traverse Forward** – From head to tail.
- **Traverse Backward** – From tail to head.

## 📚 Use Cases
- Navigators (e.g., browser history, media players)
- Undo/Redo functionality
- Implementation of Deques

## 📝 Notes
- Requires more memory due to `prev` pointer
- Flexible and efficient for insertions/deletions in both directions