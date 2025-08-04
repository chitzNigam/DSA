# 🧠 Wavelet Tree

## 🔍 What is it?
A **Wavelet Tree** is a data structure used for efficient range queries over sequences, supporting operations like rank, select, and access on compressed data.

## ✅ Key Operations
- `access(index)`
- `rank(symbol, index)`
- `select(symbol, occurrence)`

## 📚 Use Cases
- Text indexing
- Compressed data storage
- Range frequency/count queries

## 📝 Notes
- Used in FM-index and other compressed text indices
- Operates in logarithmic time over alphabet size
