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
```

## 📝 Notes
- The size of a union is the size of its largest member.
- You can use only one member at a time.
- Useful when dealing with hardware, device drivers, etc.