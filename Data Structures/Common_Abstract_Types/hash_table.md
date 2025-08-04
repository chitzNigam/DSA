# 🔐 Hash Table

## 🔍 What is it?
A **Hash Table** stores key-value pairs. It uses a **hash function** to compute an index for each key.

## 🧠 Key Operations
- `insert(key, value)`
- `search(key)`
- `delete(key)`

## 📦 Example (Python)

```python
my_dict = {"name": "Alice", "age": 25}
print(my_dict["name"])  # Output: Alice
```

## 📚 Use Cases
- Fast lookups (O(1) on average)
- Implement dictionaries, symbol tables
- Caches

## 📝 Notes
- Collisions handled using chaining or open addressing.
- Load factor affects performance.