# 🌸 Bloom Filter

## 🔍 What is it?
A **Bloom Filter** is a space-efficient, probabilistic data structure used to test whether an element is a member of a set, with a possibility of false positives.

## ✅ Key Operations
- `add(x)` – Adds element to the set
- `mightContain(x)` – Checks presence with a chance of false positives

## 📚 Use Cases
- Caches
- Databases (e.g., Bigtable, Cassandra)
- Network security

## 📝 Notes
- No false negatives
- Cannot remove elements unless using counting variant
