# Object-Oriented Programming (OOPS) in C++

A structured collection of C++ laboratory programs and assignments developed for the **Object-Oriented Programming (OOPS)** coursework. This repository covers fundamental programming concepts, transitioning progressively into core OOP paradigms such as data abstraction, encapsulation, constructors, static members, friend functions, and inheritance hierarchies.

---

## 👤 Student Information

| Field | Details |
| :--- | :--- |
| **Name** | `[Your Name Here]` |
| **USN / Roll No** | `[Your USN / Roll No]` |
| **Division / Section** | `[Your Section/Division]` |
| **Semester** | `[Your Semester]` |
| **Course** | Object-Oriented Programming (OOPS) |

> *Tip: Update the table above with your details before submitting.*

---

## 📁 Repository Structure & Course Index

```
OOPS-Programs/
├── README.md
├── .gitignore
└── Programs/
    ├── Class-01/   # Introduction to C++ syntax and basic I/O
    ├── Class-02/   # Arrays, functions, parameter passing, and strings
    ├── Class-03/   # Classes, objects, and member functions
    ├── Class-04/   # Objects as function arguments and constructors
    ├── Class-05/   # Static members and friend functions
    ├── Class-06/   # Single-level and multi-level inheritance
    └── Class-07/   # Multi-level inheritance and access specifiers
```

---

## 📚 Detailed Program Index

### 🔹 Class-01: Introduction & Basic Computations
* **`program1.cpp`**: Basic C++ program structure, standard I/O streams (`cin`/`cout`).
* **`program2.cpp`**: Calculation of rectangle area demonstrating variables and arithmetic operations.

### 🔹 Class-02: Arrays, Functions & Strings
* **`program1.cpp`**: Finding the maximum/greatest number in an array.
* **`program2.cpp`**: Conditional decision-making to find the greater of two numbers.
* **`program3.cpp`**: Swap operation using **Pass by Value**.
* **`program4.cpp`**: Swap operation using **Pass by Reference** (`&`).
* **`program5.cpp`**: Swap operation using **Pass by Pointer** (`*`).
* **`program6.cpp`**: Calculating string length using standard string utilities.
* **`program7.cpp`**: Checking if a given string is a palindrome.

### 🔹 Class-03: Classes, Objects & Methods
* **`program1.cpp`**: Introduction to `class` syntax, data members, and member functions.
* **`program2.cpp`**: Defining member functions outside the class using the scope resolution operator (`::`).
* **`program3.cpp`**: Implementation of a `Student` class with attributes and methods.
* **`program4.cpp`**: `Rectangle` class with `set_values()` and `area()` methods demonstrating multiple object instances.

### 🔹 Class-04: Objects as Arguments & Constructors
* **`program1.cpp`**: Passing objects to member functions (adding two `Time` objects).
* **`program2.cpp`**: Addition of two `Complex` numbers by passing objects as arguments.
* **`program3.cpp`**: Implementation of **Default Constructors** (`Employee` class).
* **`program4.cpp`**: Implementation of **Copy Constructors** (`Rectangle` class).
* **`program5.cpp`**: Implementation of **Parameterized Constructors** (`Employee` class).

### 🔹 Class-05: Static Members & Friend Functions
* **`program1.cpp`**: Static data members and static member functions (object counter tracking instances).
* **`program2.cpp`**: Working with classes and introducing friend function concepts.
* **`program3.cpp`**: **Friend function** accessing private data members across two independent classes (`ABC` and `XYZ`).

### 🔹 Class-06: Inheritance Fundamentals
* **`program1.cpp`**: Implementation of **Single-level Inheritance** (`Animal` -> `Dog`).
* **`program2.cpp`**: Implementation of **Multi-level Inheritance** (`Person` -> `Employee` -> `Manager`).
* **`program3.cpp`**: Exploring access specifiers (`public`, `protected`, `private`) in multi-level inheritance.

### 🔹 Class-07: Advanced Inheritance & Specifiers
* **`program1.cpp`**: Multi-level inheritance modeling vehicles (`Vehicle` -> `Car` -> `SportsCar`).
* **`program2.cpp`**: Base class access control utilizing `protected` member visibility.
* **`program3.cpp`**: Extension workspace for inheritance lab exercises.

---

## 🛠️ Compilation & Execution

Any standard C++ compiler supporting C++11 or higher (such as GCC/G++, Clang, or MSVC) can be used.

### Using GCC / G++ (Terminal / Command Prompt)

```bash
# Compile a specific program (e.g., Class-04 program1.cpp)
g++ -std=c++17 Programs/Class-04/program1.cpp -o program1

# Run on Windows:
.\program1.exe

# Run on Linux / macOS:
./program1
```

---

## 💡 Key Object-Oriented Concepts Covered

- [x] **Data Encapsulation & Abstraction**: Grouping data members and member functions within classes.
- [x] **Parameter Passing Mechanisms**: Deep dive into value, reference, and pointer semantics.
- [x] **Constructor Overloading**: Default, parameterized, and copy constructors for object initialization.
- [x] **Static Class Members**: Class-level variables and functions shared across all instances.
- [x] **Friend Functions**: Granting non-member functions privileged access to private attributes.
- [x] **Inheritance**: Single-level and multi-level inheritance hierarchies.
- [x] **Access Control**: Comprehensive usage of `public`, `protected`, and `private` specifiers.

---

## 📜 License & Academic Integrity

This repository is maintained for educational and coursework purposes.
