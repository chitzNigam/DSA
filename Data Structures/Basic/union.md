# 🧱 `union`

## 🔍 What is it?
A `union` is like a `struct`, but **all members share the same memory**. Only one member can hold a valid value at any given time.

## 🧠 Purpose
- Memory optimization.
- Useful in embedded systems, device drivers.

## 📦 Example (C)

```c
union Data {
    int i;
    float f;
    char str[20];
};
