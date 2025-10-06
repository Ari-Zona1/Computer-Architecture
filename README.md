# Computer-Architecture
Course: CS 211 — Computer Architecture & Programming Methodology, Rutgers University
Technologies: C, Makefiles, Pointers, Dynamic Memory Allocation, Data Structures, Algorithms

Overview
- This project involved designing and implementing six standalone C programs that emphasize fundamental computer science concepts such as string manipulation, recursion, data structures, and file I/O. Each program was compiled and validated through an auto-grader, ensuring correctness, efficiency, and adherence to strict C standards (-std=c99, -Wall, -Werror, -fsanitize=address,undefined).

Programs Implemented
- rot13 – String Cipher
Implemented a ROT13 substitution cipher, shifting each alphabetic character by 13 positions. Demonstrates use of character classification functions (ctype.h) and efficient single-character I/O with putchar().
- sorta – Lexicographical String Sorter
Sorted command-line arguments lexicographically using strcmp() for comparisons and implemented a sorting algorithm (e.g., bubble sort or quicksort). Reinforced understanding of string arrays and pointer manipulation.
- sudoku – Sudoku Validator and Solver
Validated 9×9 Sudoku puzzles for correctness and tested solvability of puzzles with a single missing cell. Implemented efficient matrix validation, file parsing, and logical constraint checking for rows, columns, and subgrids.
- list – Sorted Linked List Operations
Created a dynamically managed linked list supporting insert and delete operations via command-line input. After each operation, printed the list contents and size. Reinforced use of malloc/free, pointer arithmetic, and input parsing.
- mexp – Matrix Exponentiation
Read a square matrix and exponent from a file, computed M^2 through iterative matrix multiplication, and printed the result. Highlighted dynamic memory allocation, nested loops, and function modularization for clean design.
- bst – Binary Search Tree Implementation
Implemented a binary search tree (BST) supporting insert, search, delete, and print commands. Deletion handled all three cases (leaf, single child, and two children). Implemented recursive tree traversal and node deallocation to prevent memory leaks.

Project Features
- Dynamic Memory Management: Used malloc/free to handle all structures (lists, trees, and matrices).
- File and Input Handling: Supported both file I/O and stdin for data-driven operations.
- Error Handling & Robustness: Programs validated arguments, handled missing files, and gracefully exited with proper return codes.
- Build Automation: Each subproject contained an independent Makefile to compile with full sanitizers and debug symbols.
- Auto-Grader Integration: Verified 70/70 test cases for perfect scoring (100/100).

Skills Demonstrated
- Proficient in C programming and memory-safe system design
- Strong understanding of data structures (linked lists, trees, matrices)
- Competence in algorithmic problem-solving and modular coding
- Experience with compilation automation via Makefiles and command-line tools
- Debugging and validation using GCC sanitizers and structured test automation
