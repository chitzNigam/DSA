# 🌲 BK-Tree (Burkhard-Keller Tree)

## 🔍 What is it?
A **BK-Tree** is used for searching words that are within a certain edit distance (like Levenshtein distance) from a query word.

## ✅ Key Operations
- `insert(word)`
- `query(word, distance_threshold)`

## 📚 Use Cases
- Approximate string matching
- Spell-checking
- Fuzzy search engines

## 📝 Notes
- Distance metric must obey triangle inequality
- Fast approximate search for large dictionaries
