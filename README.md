# C++ Operating Systems Exercises

## Overview

This repository contains a set of **Operating Systems exercises** implemented in **C++**, developed as part of the Operating Systems course.  
The exercises include profiling and coverage tools to analyze code performance and behavior.

## Topics Covered

- C++ implementations of OS‑related exercises  
- Use of **gcov** for test coverage  
- Use of **gprof** for profiling  
- Performance analysis tools (valgrind)  
- Multiple question folders (q3, q5, q7, q8, etc.)

## Repository Structure
.vscode/
q3_gcov/
q3_gprof/
q3_valngrid/
q5/
q7/
q8/
explanation.docx

Each folder corresponds to a specific exercise or set of test cases.

## Technologies

- **C++**
- **gcov** — coverage analysis  
- **gprof** — performance profiling  
- **Valgrind** — memory and performance checks  
- Makefiles for building and analysis

## How to Run

Each folder typically contains:
- A C++ source
- Optional Makefile configurations
- Tools scripts

Example (gcov):
```bash
g++ -fprofile-arcs -ftest-coverage -o program program.cpp
./program
gcov program.cpp
```

Profiling with gprof:
```bash
g++ -pg -o program program.cpp
./program
gprof program gmon.out
```

Valgrind:
```bash
valgrind --leak-check=full ./program
```

## 📄 Explanation
Detailed explanation and answers to the exercises are in explanation.docx.
