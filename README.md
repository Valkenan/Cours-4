# Cours-4 - C++ Programming Problems

This repository contains a collection of C++ programming exercises and problems. Each problem is organized in its own directory with Visual Studio project files.

## Project Summary

A collection of solved C++ exercises and Visual Studio solution files used for "Cours 4".

This repository contains individual problems implemented in C++ (mostly Visual Studio projects and solutions). Each problem is organized into its own folder (for example `Problem1/`, `Problem2/`, ...). The code is intended for learning, practice, and demonstration of common algorithms and problem-solving techniques.

## Repository Structure (high-level)

-   `ProblemX/` — Folder for each problem (e.g. `Problem1/`, `Problem2/`, ...). Each folder typically contains:
    -   `ProblemX.cpp` — Source file with the solution
    -   `ProblemX.sln` — Visual Studio solution
    -   `ProblemX.vcxproj` and `.filters` — Visual Studio project files
-   `add probleam 10/` — (typo preserved) contains files for an additional problem (same layout)

> Note: Some folder names contain small typos (e.g. `add probleam 10`). You can rename them if desired — I didn't change repository structure here.

## How to Build and Run

There are two main ways to build and run the exercises on Windows.

-   Using Visual Studio (recommended for .sln projects):

    1. Open the desired `ProblemX.sln` file in Visual Studio.
    2. Set the configuration (Debug/Release) and platform (x86/x64).
    3. Build and Run (F5 or Ctrl+F5).

-   Using the command line (g++ / MinGW / WSL bash):

    -   From the repository root (example, build `Problem1`):

        ```bash
        mkdir -p bin
        g++ -std=c++17 -O2 "Problem1/Problem1.cpp" -o "bin/Problem1"
        ./bin/Problem1
        ```

    -   Replace `Problem1` with the desired folder and filename.

## Coding Style and Notes

-   The solutions are written as simple console programs. Some may assume specific input formatting; inspect the top of each `.cpp` file for comments or sample usage.
-   Many problems include Visual Studio project files — opening the `.sln` in Visual Studio is usually the easiest way to build and debug.

## Suggested Improvements

-   Normalize folder names (fix typos and use a consistent naming scheme such as `Problem-01`, `Problem-02`, ...).
-   Add a short README or header comment inside each problem folder describing the problem statement and sample input/output.
-   Add a `CONTRIBUTING.md` if you want external contributors to follow a style guide.

## Contribution

If you'd like help improving the repository (renaming folders, adding per-problem READMEs, adding a build script), tell me which changes you want and I can implement them.

## License & Contact

This repository does not currently include a license file. If you want to make it public, consider adding an appropriate license (for example MIT) in a `LICENSE` file.

For questions or collaboration, open an issue or contact the repository owner.

---

Updated: November 25, 2025 — Professional README drafted and applied.

The workspace contains 50 programming problems, each in a separate folder:

-   `Problem1` through `Problem50`
-   Each folder contains:
    -   `.cpp` source file with the solution
    -   `.sln` Visual Studio solution file
    -   `.vcxproj` and `.vcxproj.filters` project files

## 🚀 Getting Started

### Prerequisites

-   Visual Studio (with C++ development tools)
-   Windows operating system
-   C++ compiler

### How to Run

1. Navigate to the problem folder you want to work with
2. Open the `.sln` file in Visual Studio
3. Build and run the project (F5 or Ctrl+F5)

Alternatively, you can compile from the command line:

```bash
cd Problem<number>
cl /EHsc Problem<number>.cpp
```

## 📝 Problem List

| Problem      | Description                    |
| ------------ | ------------------------------ |
| Problem 1    | Basic C++ problem              |
| Problem 2    | Name input and output          |
| Problem 3    | Check if number is odd or even |
| Problem 4-50 | Various programming exercises  |

## 🛠️ Technologies Used

-   **Language:** C++
-   **IDE:** Visual Studio
-   **Build System:** MSBuild

## 📚 Learning Topics

This collection covers fundamental C++ concepts including:

-   Input/Output operations
-   Functions and procedures
-   Enumerations
-   Control structures
-   String manipulation
-   Data types and variables

## 📄 License

This is an educational project for learning purposes.

## 👤 Author

Valkenan

---

_Last updated: October 2025_
