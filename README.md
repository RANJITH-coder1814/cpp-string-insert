# cpp-string-insert
This repository contains a simple C++ program that demonstrates the use of the string::insert() function. The program inserts a new string at a specified position and prints the updated result. It is a beginner-friendly example to learn C++ STL string manipulation.
# 📌 C++ String insert() Example

This project demonstrates how to use the **`insert()`** function in C++ to add text at a specific position in a string.

---

## 🧠 Concept Used

- `std::string`
- `insert()` function
- Basic input/output using `cout`

---

## 🛠️ Program Code

```cpp
#include <iostream>
using namespace std;

int main() {
    string s = "hello";
    s.insert(5, " world");
    cout << s << endl;
    return 0;
}
