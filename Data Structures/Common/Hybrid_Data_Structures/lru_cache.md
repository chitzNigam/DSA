# 🧠 LRU Cache (Least Recently Used)

## 🔍 What is it?
An **LRU Cache** evicts the least recently used item when capacity is reached. Typically implemented using a hash map + doubly linked list.

## ✅ Key Operations
- `get(key)`
- `put(key, value)`

## 📚 Use Cases
- Memory caching
- Web page and session caching

## 📝 Notes
- O(1) time complexity using HashMap + Doubly Linked List
- Built-in in many languages (`collections.OrderedDict`, `functools.lru_cache`)
