# Kernel Level Programming Dec 2019

Implemented 'Threading' and 'Process Management' components in Pintos operating system in C programming language.
This involved implementing priority scheduling, priority donation, multilevel feedback queue scheduling and system call layer.

## Project 1:

-Implement Alarm Clock

-Implement priority scheduler

-Implement priority pnversion

-Implement priority donation

-Implement multi-level feedback scheduling

## Project 2:

-Argument Passing

-User Memory Access

-System Call Infrastructure

-Implement 13 system calls


## Important Directories 

• threads/

- Source code for the base kernel, which you will modify starting in project 1.

• devices/

- Source code for I/O device interfacing: keyboard, timer, disk, etc. You will modify the timer implementation in project 1. Otherwise you should have no need to change this code.

• lib/kernel/

- Parts of the C library that are included only in the Pintos kernel. Feel free to reuse this code

• tests/

- Tests for each project. You can modify this code if it helps you test your submission, but we will replace it with the originals before we run the tests.


## Files of Interest

• thread.c and thread.h

- Basic thread support. Most of project 1 work. Also see struct thread.

• synch.c and synch.h

- Synchronization primitives which you can use in all projects

• devices/timer.c and devices/timer.h

- Timer ticks, has to be modified for project 1

• lib/kernel/list.c

- Linked list implementation, feel free to reuse

• init.c and init.h

- Kernel initialization, including main(), the kernel's "main program."

