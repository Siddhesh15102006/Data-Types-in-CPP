# 🧪 Experiment: Data Types in C++

---

## ✅ Q1: Demonstration of Data Types in C++

---

### 🎯 Aim:

To write a C++ program that demonstrates the use of **different data types** including `int`, `float`, `double`, `char`, `bool`, and `string`.

---

### 📚 Theory:

**Data types** in C++ define the type of data a variable can hold. Choosing the correct data type is important for memory management and correct processing of values.

#### Common Data Types in C++:

| Data Type | Description                          | Example Value |
| --------- | ------------------------------------ | ------------- |
| `int`     | Integer (whole numbers)              | 10            |
| `float`   | Single-precision decimal number      | 3.14f         |
| `double`  | Double-precision decimal number      | 3.14159       |
| `char`    | Single character                     | 'A'           |
| `bool`    | Boolean (true or false)              | true, false   |
| `string`  | Text string (from `<string>` header) | "Hello"       |

Each data type occupies a different amount of memory, and is used based on the nature of the value being stored.

---

### 🧠 Logic:

1. Declare variables of each basic data type.
2. Initialize each variable with a sample value.
3. Use `cout` to display their values and sizes using `sizeof()`.

---

### 💡 Syntax:

```cpp
int a = 10;
float b = 3.14f;
double c = 3.14159;
char d = 'A';
bool e = true;
string f = "Hello";

sizeof(variable); // Returns size in bytes
```

---

### 🧾 Code:

```cpp
// Q1: Demonstration of Data Types in C++
#include <iostream>
#include <string>  // For string type
using namespace std;

int main() {
    int intVar = 10;
    float floatVar = 3.14f;
    double doubleVar = 3.14159;
    char charVar = 'A';
    bool boolVar = true;
    string stringVar = "Hello, World!";

    cout << "Integer value: " << intVar << " | Size: " << sizeof(intVar) << " bytes" << endl;
    cout << "Float value: " << floatVar << " | Size: " << sizeof(floatVar) << " bytes" << endl;
    cout << "Double value: " << doubleVar << " | Size: " << sizeof(doubleVar) << " bytes" << endl;
    cout << "Character value: " << charVar << " | Size: " << sizeof(charVar) << " byte" << endl;
    cout << "Boolean value: " << boolVar << " | Size: " << sizeof(boolVar) << " byte" << endl;
    cout << "String value: " << stringVar << " | Size: " << sizeof(stringVar) << " bytes (object size)" << endl;

    return 0;
}
```

---

### ✅ Sample Output:

```
Integer value: 10 | Size: 4 bytes
Float value: 3.14 | Size: 4 bytes
Double value: 3.14159 | Size: 8 bytes
Character value: A | Size: 1 byte
Boolean value: 1 | Size: 1 byte
String value: Hello, World! | Size: 32 bytes (object size)
```
---

### 📌 Conclusion:

This program successfully demonstrates the use of **basic data types in C++**. It shows how to declare, initialize, and display variables, along with checking their memory size. Understanding data types is essential for efficient memory usage and correct program behavior.

---
