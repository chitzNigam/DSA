# ⛓️ Heap (Priority Queue)

## 🔍 What is it?
A **Heap** is a binary tree-based structure that satisfies the **heap property**:
- **Min-Heap**: Parent ≤ Children
- **Max-Heap**: Parent ≥ Children

## 🧠 Key Operations
- `insert(x)`
- `extractMin()` or `extractMax()`
- `heapify()`

## 📦 Example (C++)

```cpp
priority_queue<int> maxHeap;
priority_queue<int, vector<int>, greater<int>> minHeap;
