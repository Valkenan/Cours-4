# Cours-4 - C++ Programming Problems

A collection of **50 C++ programming exercises** designed for learning fundamental programming concepts. Each problem is organized in its own directory with Visual Studio project files.

## 📋 Overview

This repository contains individual problems implemented in C++ using Visual Studio projects and solutions. The code is intended for learning, practice, and demonstration of common algorithms and problem-solving techniques.

## 📁 Repository Structure

```
Cours-4/
├── probleam1/          # Problem 1 - Print Name
├── Problem2/           # Problem 2 - Read and Print Name
├── Problem3/           # Problem 3 - Odd/Even Checker
├── Problem4/           # Problem 4 - Job Application (Struct)
├── probleam5/          # Problem 5 - Candidate Evaluation
├── probleam6/          # Problem 6 - Full Name Builder
├── probleam7/          # Problem 7 - Half Number Calculator
├── probleam8/          # Problem 8 - Pass/Fail Checker
├── probleam9/          # Problem 9 - Sum of 3 Numbers
├── add probleam 10/    # Problem 10 - Average Calculator
├── Problem11-50/       # Additional exercises
└── README.md
```

Each folder contains:

-   `.cpp` — Source file with the solution
-   `.sln` — Visual Studio solution file
-   `.vcxproj` and `.vcxproj.filters` — Project files

## 🚀 Getting Started

### Prerequisites

-   **Visual Studio** (with C++ development tools)
-   Windows operating system
-   C++ compiler (MSVC, MinGW, or g++)

### Building and Running

#### Option 1: Visual Studio (Recommended)

1. Open the desired `.sln` file in Visual Studio
2. Set configuration (Debug/Release) and platform (x86/x64)
3. Build and Run (`F5` or `Ctrl+F5`)

#### Option 2: Command Line (MSVC)

```bash
cd Problem<number>
cl /EHsc Problem<number>.cpp
Problem<number>.exe
```

#### Option 3: Command Line (g++ / MinGW)

```bash
mkdir -p bin
g++ -std=c++17 -O2 "Problem1/Problem1.cpp" -o "bin/Problem1"
./bin/Problem1
```

## 📝 Problem List

| #     | Problem         | Description                                              |
| ----- | --------------- | -------------------------------------------------------- |
| 1     | probleam1       | Print a hardcoded name using functions                   |
| 2     | Problem2        | Read name from user and display it                       |
| 3     | Problem3        | Check if a number is odd or even (using enum)            |
| 4     | Problem4        | Job application - check age and driving license (struct) |
| 5     | probleam5       | Candidate evaluation with recommendations                |
| 6     | probleam6       | Build full name (normal or reversed)                     |
| 7     | probleam7       | Calculate half of a number                               |
| 8     | probleam8       | Pass/Fail grade checker (mark >= 50)                     |
| 9     | probleam9       | Sum of three numbers (reference parameters)              |
| 10    | add probleam 10 | Calculate average of three marks                         |
| 11    | Problem11       | Pass/Fail based on average of three marks                |
| 12-29 | Problem12-29    | Various programming exercises                            |
| 30    | Problem30       | Factorial calculator                                     |
| 31-49 | Problem31-49    | Advanced exercises                                       |
| 50    | Problem50       | PIN-based login system (3 attempts)                      |

## 📚 Learning Topics Covered

This collection covers fundamental C++ concepts including:

| Category         | Topics                                |
| ---------------- | ------------------------------------- |
| **Basics**       | Input/Output, Variables, Data Types   |
| **Functions**    | Parameters, Return Values, References |
| **Structures**   | `struct`, Enumerations (`enum`)       |
| **Control Flow** | `if/else`, `do-while`, `for` loops    |
| **Strings**      | String manipulation, `getline()`      |
| **Algorithms**   | Factorial, Sum, Average calculations  |
| **Logic**        | Validation, Authentication patterns   |

## 🛠️ Technologies Used

-   **Language:** C++ (C++11/14/17)
-   **IDE:** Visual Studio
-   **Build System:** MSBuild
-   **Platform:** Windows

## 📌 Notes

> Some folder names contain typos (e.g., `probleam` instead of `problem`, `add probleam 10`). These are preserved from the original structure but can be renamed for consistency.

## 🤝 Contributing

Contributions are welcome! Feel free to:

-   Fix typos in folder names
-   Add problem descriptions/comments
-   Improve code quality
-   Add new exercises

## 📄 License

This is an educational project for learning purposes.

## 👤 Author

**Valkenan**

---

_Last updated: November 25, 2025_
