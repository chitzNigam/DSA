# 🧱 `enum` (Enumeration)

## 🔍 What is it?
An `enum` defines a set of **named constant values**. It helps make code more readable by giving meaningful names to numbers.

## 🧠 Purpose
- Represent fixed sets of related constants (e.g., days, directions, states).
- Improve code clarity over numeric constants.

## 📦 Example (C)

```c
enum Day { MON, TUE, WED, THU, FRI, SAT, SUN };
```

## 📝 Notes
- Default values start from 0: MON = 0, TUE = 1, etc.
- You can assign custom values:
    ```c
    enum Status { OK = 200, NOT_FOUND = 404 };
    ```
- Available in C, C++, Java, and Python (Enum class).