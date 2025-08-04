# ⏳ Lazy Segment Tree

## 🔍 What is it?
An optimized version of Segment Tree for frequent **range updates**.

## ✅ Key Operations
- `rangeUpdate(l, r, val)`
- `rangeQuery(l, r)`

## 📚 Use Cases
- Range addition/multiplication
- Interval tagging

## 📝 Notes
- Avoids repeated updates by deferring them (lazy propagation)
- Time: O(log n)
