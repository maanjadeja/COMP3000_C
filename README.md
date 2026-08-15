# COMP 3000: Operating Systems

## Course Overview

COMP 3000 is an Operating Systems course at Carleton University that provides a first course in operating systems, stressing fundamental issues in design. The course covers:

- Process management
- Memory management
- File systems
- Input/Output (I/O) systems
- Synchronization and deadlock
- Virtual memory
- Scheduling algorithms
- Disk management
- Security and protection mechanisms

**Prerequisites:** COMP 2402, COMP 2002, COMP 2003 (or equivalents: SYSC 3001, SYSC 2002, SYSC 3003)  
**Credits:** 0.5  
**Format:** 3 hours of lectures per week

---

## Assignments

### Assignment 1: Memory Management and System Calls

Exploration and analysis of memory management in C programs and understanding of system calls in Unix/Linux systems.

**Topics Covered:**
- Memory viewing and memory layout analysis
- System calls (syscalls) - user vs kernel mode
- Memory allocation with malloc and mallopt
- Memory threshold management (M_MMAP_THRESHOLD, M_TRIM_THRESHOLD)
- Process memory segments (heap, stack, global data)
- Sudo command and privilege escalation

**Deliverables:**
- Memory viewing C programs (3000memview_original.c, 3000memview_modified.c)
- Analysis of syscall differences and portability
- Comparison of syscall implementations
- Diff files showing memory allocation modifications

---

### Assignment 2: Shell Implementation

Design and implementation of a custom Unix shell with process management and command parsing capabilities.

**Topics Covered:**
- Process creation and management (fork, exec)
- Command parsing and argument handling
- Signal handling
- User login functionality
- Process waiting and status handling
- File descriptors and I/O redirection

**Deliverables:**
- Shell implementation (3000shell.c, 3000shellMODIFIED.c)
- User login patched version (3000userlogin-patched.c)
- Diff files documenting modifications
- Written analysis and answers to assignment questions

---

### Assignment 3: [Operating Systems Concepts]

[Assignment 3 details - refer to Assignment3.pdf]

**Deliverables:**
- Assignment3.pdf

---

### Assignment 4: [Operating Systems Concepts]

[Assignment 4 details - refer to Assignment4.pdf]

**Deliverables:**
- Assignment4.pdf

---

## Repository Structure

```
COMP3000-C/
├── Assignment1/
│   ├── 3000memview_original.c          # Original memory viewing program
│   ├── 3000memview_modified.c          # Modified version with malloc threshold
│   ├── 3000.diff.txt                   # Diff showing modifications
│   ├── maanjadeja-comp3000-assign1.txt # Written answers
│   ├── Assignment1-updated.pdf         # Assignment specification
│   └── tester/                         # Test files and checker
├── Assignment2/
│   ├── 3000shell.c                     # Original shell implementation
│   ├── 3000shellMODIFIED.c             # Modified shell with enhancements
│   ├── 3000userlogin-patched.c         # User login functionality
│   ├── 3000shell.diff                  # Diff showing modifications
│   ├── Assignment2.pdf                 # Assignment specification
│   └── maanjadeja-comp3000-assign2.tar.gz # Submission archive
├── Assignment3/
│   └── Assignment3.pdf                 # Assignment specification and work
├── Assignment4/
│   └── Assignment4.pdf                 # Assignment specification and work
├── Tutorials/
│   ├── Tutorial explanations
│   └── Tutorial test cases
└── README.md
```

---

## License

**All Rights Reserved - No Permission for External Use**

This code and all associated materials are the exclusive property of the author. Unauthorized copying, modification, or use of any part of this work is strictly prohibited. This work is provided for educational purposes only within Carleton University.
