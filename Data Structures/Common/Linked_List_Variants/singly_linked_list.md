# 🔗 Singly Linked List

## 🔍 What is it?
A **Singly Linked List** is a linear data structure where each element (called a node) contains:
- A value
- A pointer to the next node in the list

It allows **one-directional traversal** — from the head (first node) to the tail (last node).

## 🧱 Node Structure (C)
```c
struct Node {
    int data;
    struct Node* next;
};
```

## ✅ Key Operations
- **Insert at Beginning** – Add a new node before the head.
- **Insert at End** – Append a new node at the tail.
- **Delete by Value** – Remove a node that matches a given value.
- **Search** – Find a node with a specific value.
- **Traverse** – Visit all nodes in order.

## 📚 Use Cases
- Implementation of **Stacks** and **Queues**
- Memory-efficient list when frequent **insertions/deletions** are needed
- Symbol tables in compilers

## 📝 Notes
- Simpler than other lists, but no backward traversal
- Last node points to `NULL`
- Easy to implement but less powerful than doubly or circular variants