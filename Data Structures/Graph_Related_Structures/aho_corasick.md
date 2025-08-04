# 🧵 Aho-Corasick Trie

## 🔍 What is it?
The **Aho-Corasick Trie** is a string matching data structure that allows simultaneous searching for multiple patterns.

## ✅ Key Operations
- `buildTrie(patterns)` – Builds a trie from multiple string patterns
- `search(text)` – Searches for all occurrences of the patterns in the text

## 📚 Use Cases
- Intrusion detection systems
- Spam filtering
- Lexical analyzers
- DNA sequence searching

## 📝 Notes
- Combines trie with failure links (like KMP)
- Time Complexity:
  - Building: O(M), where M is the total length of all patterns
  - Searching: O(N + Z), where N is the text length and Z is the number of matches
