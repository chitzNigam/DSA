# 🧠 Counting Bloom Filter

## 🔍 What is it?
A **Counting Bloom Filter** is an extension of the Bloom filter that allows for element deletions by storing counters instead of single bits.

## ✅ Key Operations
- `insert(item)`
- `delete(item)`
- `query(item)`

## 📚 Use Cases
- Caches that need item eviction
- Databases with approximate membership and deletions
- Network packet filtering

## 📝 Notes
- Each bit in standard Bloom filter is replaced with a small counter
- Slightly higher space cost than a regular Bloom filter
