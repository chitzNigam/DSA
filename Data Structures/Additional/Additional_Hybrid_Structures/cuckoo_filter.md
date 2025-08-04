# 🧠 Cuckoo Filter

## 🔍 What is it?
A **Cuckoo Filter** is a probabilistic data structure for approximate membership queries, supporting deletion like a counting Bloom filter but using a hash table with cuckoo hashing.

## ✅ Key Operations
- `insert(item)`
- `delete(item)`
- `query(item)`

## 📚 Use Cases
- Network intrusion detection systems
- Databases and caches
- Approximate set representations with deletion

## 📝 Notes
- Better space efficiency than counting Bloom filter
- Constant-time lookups
