# 🌲 Trie (Prefix Tree)

## 🔍 What is it?
A **Trie** is a tree-like data structure used for **storing strings**. Each node represents a character.

## 🧠 Key Operations
- `insert(word)`
- `search(word)`
- `startsWith(prefix)`

## 📦 Node Structure

```cpp
struct TrieNode {
    TrieNode* children[26];
    bool isEndOfWord;
};
```

## 📚 Use Cases
- Auto-complete
- Spell checking
- IP routing

## 📝 Notes
- Space intensive but fast prefix search (O(m) time).
- Variants: Compressed Trie, Suffix Trie.
