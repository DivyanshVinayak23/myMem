# myMem
**Replaces sbrk() with mmap() for Enhanced Efficiency**

This C library provides a custom memory manager that implements malloc(), realloc(), free(), and calloc() functions, leveraging mmap() for superior performance compared to the traditional sbrk() approach.

Key Features:

️ Speed Boost: mmap() enables memory allocation in larger chunks, reducing system calls and fragmentation, leading to faster memory allocation and deallocation.


** Efficient Memory Management:** Provides a controlled environment for memory usage, optimizing performance for your applications.
