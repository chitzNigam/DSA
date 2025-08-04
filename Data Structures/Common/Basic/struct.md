# 🧱 `struct` (Structure)

## 🔍 What is it?
A `struct` is a composite data type that groups **multiple variables of different types** under one name. It is used mainly in **C and C++** to represent real-world entities.

## 🧠 Purpose
- Group logically related variables (data only).
- Useful for modeling objects like `Student`, `Book`, etc.

## 📦 Example (C)

```c
struct Student {
    int id;
    char name[50];
    float marks;
};
```

## 📝 Notes
- Memory is allocated for all members.
- Access members using the dot (.) operator.
- You can create arrays of structs