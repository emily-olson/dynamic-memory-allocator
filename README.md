# Dynamic Memory Allocator – Computer Systems Project

This project was completed as part of the *Computer Systems* course at Brown University. The objective was to implement a custom dynamic memory allocator that mimics the behavior of the standard `malloc` and `free` functions in C. This allocator manages memory from a simulated heap using custom metadata, alignment logic, and free list operations.

I coded the implementation in C, learning how memory management works at a low level in operating systems and runtime environments.

---

## Project Summary
- **Language**: C
- **Domain**: Operating systems, memory management
- **Functionality**: Simulate heap allocation behavior (`malloc`, `free`, `calloc`, etc.)

---

## Key Features

- **Free List Management**: Maintains a singly-linked free list of reusable memory blocks to avoid unnecessary allocations.
- **Memory Alignment**: Ensures all allocations are aligned to system requirements to avoid memory access errors.
- **Block Splitting**: Implements logic to split large blocks into smaller ones if only part of the memory is requested.
- **Error Handling**: Detects invalid `free()` calls, double frees, and out-of-memory conditions.

---

Code is private to comply with academic integrity policies. I’m happy to provide an overview or discuss my implementation with recruiters upon request.

