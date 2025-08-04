# 🌀 Stack (LIFO)

## 🔍 What is it?
A **Stack** is a linear data structure that follows the **Last-In, First-Out (LIFO)** principle. The last element inserted is the first one to be removed.

## 🧠 Key Operations
- `push(x)`: Add element `x` to the top.
- `pop()`: Remove and return the top element.
- `peek()/top()`: View the top element without removing.
- `isEmpty()`: Check if the stack is empty.

## 📦 Example (C++)

```cpp
stack<int> s;
s.push(10);
s.push(20);
s.pop(); // Removes 20
```

## 📚 Use Cases
- Function call stack
- Undo/Redo functionality
- Balanced parentheses
- DFS (Depth-First Search)

## 📝 Notes
- Can be implemented using arrays or linked lists.
- Often provided as a built-in data structure in high-level languages.