---
name: 'Highly Comprehensive and Efficient Memory Safety Enforcement with Pointer Tagging'
speakers:
  - Xiaolei Wang
  - Bin Zhang
  - Chaojing Tang
room: 'DSN2024'
categories:
  - Regular papers
---


Memory safety issues greatly affect the dependability of all software systems. As such, many sanitizers have been proposed to enhance memory safety at the development or deployment phase. However, existing solutions still face many practical challenges, including significant performance overhead, low compatibility with legacy code, and non-comprehensive protection for various program objects and sub-objects.

In this paper, we propose CECSan, an integrated highly Compatible, Efficient and Comprehensive compiler-based Sanitizer to detect spatial and temporal memory errors in C/C++ programs. CECSan enforces full memory safety using a integration of pointer tagging, compact metadata table, compiler instrumentation and optimzation. The pointer tagging encodes object metadata index within native pointer itself, while instrumentation adds metadata retrival and safety checks for all memory access. Specifically, CECSan advantages over previous sanitizers by simultaneously: 1) supporting memory safety guarantee on sub-object granularity; 2) significantly reducing performance overhead with various optimization strategies. 3) removing the need of a customized memory allocator and avoiding object memory layout changes to improve compatibility. Evaluations on our prototype show that, CECSan outperforms known sanitizers by achieving a bug detection rate of 100% on the Juliet Test Suite. Additionally, CECSan significantly reduces memory consumption while maintaining an acceptable level of runtime overhead.

