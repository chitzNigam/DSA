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
```

## 📚 Use Cases
- Priority queues
- Dijkstra’s algorithm
- Scheduling

## 📝 Notes
- Binary heap is most common (array-based).
- Time complexity: insert and delete → O(log n)