# C++ Learning Notes & Examples 📘

**Purpose:** This repository is a personal study space for learning C++. It contains notes, example programs, and small projects to help reinforce concepts.

---

## Table of Contents
- [About](#about)
- [Repository Structure](#repository-structure)
- [How to run examples](#how-to-run-examples) 
---

## About
This repository is a personal study space for learning C++. It contains notes, small example programs, and small projects to help reinforce concepts.
This repository is for personal use and study — it is not intended for external contributions, and there is no license included.

---

## Repository Structure
A suggested structure (adjust as needed):

- `notes/` — Markdown notes explaining concepts and summaries.
- `examples/` — Small, single-concept C++ programs (one example per folder with a short README).
- `projects/` — Small practice projects or experiments.
- `README.md` — This file.

Example:

```
C++/
├─ notes/
├─ examples/
├─ projects/
└─ README.md
```

---

## How to run examples 🔧
You can use a compiler like `g++` (MinGW/MSYS2) or MSVC (Visual Studio) or build with CMake.

Quick commands:

- g++ (single-file):

```bash
g++ -std=c++20 -O2 -Wall examples/hello-world/main.cpp -o build/hello
./build/hello
```

- CMake (recommended for multi-file projects):

```bash
mkdir -p build && cd build
cmake ..
cmake --build .
```

- Visual Studio: Open the project or use `cl.exe` from the Developer Command Prompt.

Notes:
- Use `-std=c++17` or `-std=c++20` depending on which features you want to use.
- Add `-Wall -Wextra -Werror` to enable helpful warnings.

---


## Recommended tools & resources 💡
- Compiler: GCC (MinGW/MSYS2) or MSVC (Visual Studio)
- Editor: Visual Studio Code + C/C++ extension
- Build system: CMake

Books & online resources:
- "C++ Primer" (Lippman et al.)
- "Effective Modern C++" (Scott Meyers)
- cppreference.com — for quick API and language reference
- LearnCpp.com — tutorial-style explanations

---

