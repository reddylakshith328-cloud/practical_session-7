# OSSP Practical Session 7
## Understanding Linux Process Address Space

### Aim
To write a C program that displays the addresses of different parts of a Linux process address space and analyze the memory layout of a running process.

### Programs

#### 1. memory_layout.c
Displays the addresses of:
- Code/Text segment
- Global variable
- Static variable
- BSS segment
- Heap
- Stack

Compile and run:

```bash
gcc -Wall -Wextra -g memory_layout.c -o memory_layout
./memory_layout

