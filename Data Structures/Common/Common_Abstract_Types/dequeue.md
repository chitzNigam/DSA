
# 🔁 Deque (Double-Ended Queue)

## 🔍 What is it?
A **Deque** allows insertion and deletion from **both front and rear ends**.

## 🧠 Key Operations
- `push_front(x)`, `push_back(x)`
- `pop_front()`, `pop_back()`

## 📦 Example (C++)

```cpp
deque<int> dq;
dq.push_front(10);
dq.push_back(20);
dq.pop_front(); // Removes 10
```

## 📚 Use Cases
- Sliding window problems
- LRU Cache
- Palindrome checker

## 📝 Notes
- More flexible than stacks and queues.
- Can be implemented using doubly linked lists.