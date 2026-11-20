# DSA01 Coursework

**Student** S Vinoth Kumar  
**Register number** 192471006

Five C++ assignments with source code, reports, and validation evidence.

## Assignments

| Assignment | Topics | Guide |
| --- | --- | --- |
| [1](assignments/assignment-1/) | Namma Metro smart-card fares, integer arithmetic, and object-oriented design | [Build and results](assignments/assignment-1/README.md) |
| [2](assignments/assignment-2/) | References, function overloading, transaction and ticketing examples, and circular buffers | [Build and results](assignments/assignment-2/README.md) |
| [3](assignments/assignment-3/) | Constructors, destructors, deep copying, and operator overloading | [Build and results](assignments/assignment-3/README.md) |
| [4](assignments/assignment-4/) | Reusable class hierarchies, inheritance, and object lifetimes | [Build and results](assignments/assignment-4/README.md) |
| [5](assignments/assignment-5/) | Runtime polymorphism, virtual destructors, and exception handling | [Build and results](assignments/assignment-5/README.md) |

## Build and run

Start in the folder for the assignment you want to run, then follow its README for compiler settings, inputs, and expected output. Treat any instruction that says to run a command from the repository root as relative to that assignment's folder.

For example, run Assignment 2's first program from the root of this repository.

```sh
cd assignments/assignment-2
g++ -std=c++17 -Wall -Wextra Task01/main.cpp -o /tmp/dsa01-assignment2-task01
/tmp/dsa01-assignment2-task01
```

Some tasks use intentionally invalid examples to demonstrate compiler diagnostics. Check the assignment guide before compiling those files.
