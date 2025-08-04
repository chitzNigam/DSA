# 🔁🔄 Circular Doubly Linked List

## 🔍 What is it?
A **Circular Doubly Linked List** is a combination of doubly and circular lists. Each node:
- Points to both the **next** and **previous** nodes
- The last node's `next` points to the **head**, and the head's `prev` points to the **tail**

## 🧱 Node Structure (C)
```c
struct Node {
    int data;
    struct Node* next;
    struct Node* prev;
};
```

## ✅ Key Operations
- **Insert Before/After Any Node**
- **Delete Any Node**
- **Traverse Forward or Backward** from any node

## 📚 Use Cases
- Media players (next/prev track)
- Tab switching in applications
- Games with player turns

## 📝 Notes
- More memory usage, but more flexible
- Supports full circular and bidirectional navigation