
# 🚦 Queue (FIFO)

## 🔍 What is it?
A **Queue** is a linear data structure that follows the **First-In, First-Out (FIFO)** principle. The first element added is the first to be removed.

## 🧠 Key Operations
- `enqueue(x)`: Add element `x` to the rear.
- `dequeue()`: Remove and return the front element.
- `peek()/front()`: View the front element.
- `isEmpty()`: Check if queue is empty.

## 📦 Example (C++)

```cpp
queue<int> q;
q.push(10);
q.push(20);
q.pop(); // Removes 10
