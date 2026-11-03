# Object-Oriented Programming (OOPS) in C++

A structured collection of C++ laboratory programs and assignments developed for the **Object-Oriented Programming (OOPS)** coursework. This repository covers fundamental programming concepts, transitioning progressively into core OOP paradigms such as data abstraction, encapsulation, constructors, static members, friend functions, inheritance hierarchies, virtual base classes, runtime polymorphism, operator overloading, and exception handling.

---

## 👤 Student Information

| Field | Details |
| :--- | :--- |
| **Name** | Bhoomi B Hallur |
| **USN** | 01FE23BEC235 |
| **Division** | E |
| **Semester** | 7th |
| **Course** | Object-Oriented Programming (OOPS) |

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
    ├── Class-07/   # Multi-level inheritance and access specifiers
    ├── Class-08/    # Constructor initialization lists in derived classes
    ├── Class-09/   # Multiple inheritance implementation
    ├── Class-10/   # Virtual base classes and runtime polymorphism
    ├── Class-11/   # Virtual functions, abstract classes, and operator overloading
    └── Class-12/   # Binary operator overloading and exception handling
```

---

## 📚 Detailed Program Index

### 🔹 Class-01: Introduction & Basic Computations
* **`program1.cpp`**: Basic C++ program structure, primitive data types, and standard I/O streams (`cin`/`cout`).
* **`program2.cpp`**: Calculation of rectangle area demonstrating variables and arithmetic expressions.

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
* **`program3.cpp`**: Implementation of **Default Constructors** (`employee` class).
* **`program4.cpp`**: Implementation of **Copy Constructors** (`rect` class).
* **`program5.cpp`**: Implementation of **Parameterized Constructors** (`Employee` class).

### 🔹 Class-05: Static Members & Friend Functions
* **`program1.cpp`**: Static data members and static member functions (object counter tracking instances).
* **`program2.cpp`**: Working with classes and introducing friend function concepts.
* **`program3.cpp`**: **Friend function** accessing private data members across two independent classes (`ABC` and `XYZ`).

### 🔹 Class-06: Inheritance Fundamentals
* **`program1.cpp`**: Implementation of **Single-level Inheritance** (`Animal` -> `Dog`).
* **`program2.cpp`**: Implementation of **Multi-level Inheritance** (`Person` -> `Student` -> `IT_Student`).
* **`program3.cpp`**: Exploring access specifiers (`public`, `protected`, `private`) in multi-level inheritance.

### 🔹 Class-07: Advanced Inheritance & Specifiers
* **`program1.cpp`**: Multi-level inheritance modeling vehicles (`Vehicle` -> `Car` -> `SportsCar`).
* **`program2.cpp`**: Base class access control utilizing `protected` member visibility in derived classes.

### 🔹 Class-08: Constructor Initialization in Inheritance
* **`program1.cpp`**: Constructor initialization in single-level inheritance (`Animal` base class).
* **`program2.cpp`**: Multi-level inheritance hierarchy (`Person` -> `Student` -> `IT_Student`).
* **`program3.cpp`**: Constructor chaining demonstration highlighting requirements for base constructors.
* **`program4.cpp`**: Derived class constructor passing arguments to parameterized base class constructor.
* **`program5.cpp`**: Multiple inheritance with constructor initialization lists (`Student` and `Test` into `Result`).
* **`program6.cpp`**: Student test score processing and percentage calculation using multiple inheritance.

### 🔹 Class-09: Multiple Inheritance
* **`program1.cpp`**: Implementation of multiple inheritance modeling physical properties (`Liquid` and `Fuel` -> `Petrol`).

### 🔹 Class-10: Virtual Base Classes & Polymorphism
* **`program1.cpp`**: Multipath inheritance illustrating variable ambiguity (the diamond problem).
* **`program2.cpp`**: Resolving inheritance ambiguity using **Virtual Base Classes** (`virtual public`).
* **`program3.cpp`**: Runtime polymorphism (late binding) using the `virtual` keyword and base pointers.
* **`program4.cpp`**: Comparison of static resolution vs dynamic dispatch (`override` keyword).

### 🔹 Class-11: Abstract Classes & Operator Overloading
* **`program1.cpp`**: Late binding demonstration using base class pointers with virtual functions.
* **`program2.cpp`**: Base class `Shape` with virtual `draw()` overridden by `Circle`, `Rectangle`, and `Triangle`.
* **`program3.cpp`**: Polymorphic invocation using an array of base class pointers (`Shape* arr[]`).
* **`program4.cpp`**: **Abstract Class** implementation with pure virtual function (`virtual float disp_mileage() = 0`).
* **`program5.cpp`**: Binary operator overloading (`+`) for complex number addition.
* **`program6.cpp`**: Binary operator overloading (`-`) for complex number subtraction.
* **`program7.cpp`**: Unary operator overloading for pre-increment (`++`).
* **`program8.cpp`**: Unary operator overloading for pre-decrement (`--`).

### 🔹 Class-12: Binary Operator Overloading & Exception Handling
* **`program1.cpp`**: Binary operator overloading (`+`) for string concatenation (`String_Concat` class).
* **`program2.cpp`**: Fundamentals of exception handling using `try`, `throw`, and `catch`.
* **`program3.cpp`**: Exception handling validation ensuring non-zero operands for multiplication.
* **`program4.cpp`**: Product validation exception handling with custom error messages.
* **`program5.cpp`**: Handling divide-by-zero errors gracefully with exceptions.
* **`program6.cpp`**: Analysis of unhandled exceptions and runtime error propagation.

---

## 🛠️ Compilation & Execution

Any standard C++ compiler supporting C++11 or higher (such as GCC/G++, Clang, or MSVC) can be used.

### Using GCC / G++ (Terminal / Command Prompt)

```bash
# Compile a specific program (e.g., Class-11 program5.cpp)
g++ -std=c++17 Programs/Class-11/program5.cpp -o program5

# Run on Windows:
.\program5.exe

# Run on Linux / macOS:
./program5
```

---

## 💡 Key Object-Oriented Concepts Covered

- [x] **Data Encapsulation & Abstraction**: Grouping data members and member functions within classes.
- [x] **Parameter Passing Mechanisms**: Deep dive into value, reference, and pointer semantics.
- [x] **Constructor Overloading**: Default, parameterized, and copy constructors for object initialization.
- [x] **Constructor Initialization Lists**: Efficient base-class and member initialization in derived classes.
- [x] **Static Class Members**: Class-level variables and functions shared across all instances.
- [x] **Friend Functions**: Granting non-member functions privileged access to private attributes.
- [x] **Inheritance Types**: Single-level, multi-level, and multiple inheritance hierarchies.
- [x] **Access Control**: Comprehensive usage of `public`, `protected`, and `private` specifiers.
- [x] **Virtual Base Classes**: Eliminating multipath diamond ambiguity in multiple inheritance.
- [x] **Runtime Polymorphism & Virtual Functions**: Function overriding and dynamic binding via base class pointers.
- [x] **Abstract Classes & Pure Virtual Functions**: Establishing interface contracts using `= 0`.
- [x] **Operator Overloading**: Overloading unary (`++`, `--`) and binary (`+`, `-`) operators for custom classes.
- [x] **Exception Handling**: Structured error handling with `try`, `catch`, and `throw` blocks.

---

## 📜 License & Academic Integrity

This repository is maintained for educational and coursework purposes.
