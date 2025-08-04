# 🧱 `class`

## 🔍 What is it?
A `class` is a user-defined blueprint for creating objects. It encapsulates **data (attributes)** and **functions (methods)**.

## 🧠 Purpose
- Support Object-Oriented Programming (OOP)
- Enable:
  - Encapsulation
  - Abstraction
  - Inheritance
  - Polymorphism

## 📦 Example (C++)

```cpp
class Student {
private:
    int id;
    float marks;

public:
    void setData(int i, float m) {
        id = i;
        marks = m;
    }

    void display() {
        cout << "ID: " << id << ", Marks: " << marks << endl;
    }
};
