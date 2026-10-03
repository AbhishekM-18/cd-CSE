# 🖥️ Systems & Core Computing

Systems & Core Computing focuses on understanding what happens underneath applications — how computers execute programs, how operating systems manage resources, how machines communicate, and how large computing systems work together.

It connects:

- Computer Architecture
- Operating Systems
- Computer Networks
- Distributed Systems
- Linux
- Systems Programming
- Embedded Systems
- Concurrency
- Performance Engineering

Systems knowledge is useful across software engineering, cloud, DevOps, cybersecurity, backend development, databases, and embedded systems.

---

## 🧭 The Systems Landscape

```text
Systems & Core Computing
│
├── Computer Architecture
│
├── Operating Systems
│
├── Computer Networks
│
├── Distributed Systems
│
├── Systems Programming
│
└── Embedded Systems
```

These areas overlap heavily and are often learned together.

---

# 🧠 Computer Architecture

Computer Architecture explains how a computer executes instructions and manages data at the hardware level.

### Learn

- CPU
- Registers
- ALU
- Control Unit
- Instruction Set Architecture
- Memory hierarchy
- Cache
- RAM
- Storage
- Pipelining
- Interrupts
- I/O
- Buses
- Performance

### Understand This Flow

```text
Program
   ↓
Compiler / Interpreter
   ↓
Machine Instructions
   ↓
CPU
   ↓
Memory / I/O
   ↓
Hardware
```

Understanding this layer helps explain why programs behave and perform the way they do.

---

# 🐧 Operating Systems

An Operating System manages hardware resources and provides services to applications.

### Learn

- Processes
- Threads
- CPU scheduling
- Memory management
- Virtual memory
- File systems
- Synchronization
- Deadlocks
- System calls
- I/O
- Protection
- Virtualization

### Important Questions

You should eventually be able to explain:

- What happens when a program starts?
- What is a process?
- How is a thread different from a process?
- What happens during a context switch?
- How does virtual memory work?
- How does a program communicate with the OS?
- How does a file get read from storage?
- Why do processes need synchronization?

---

# 🌐 Computer Networks

Computer Networks explains how computers and devices communicate.

### Learn

- OSI model
- TCP/IP model
- IP addressing
- Subnetting
- MAC addresses
- Ethernet
- ARP
- TCP
- UDP
- DNS
- DHCP
- HTTP
- HTTPS
- Routing
- NAT
- Firewalls
- VPNs

### Understand This Flow

```text
Browser
   ↓
DNS
   ↓
IP Address
   ↓
TCP / TLS
   ↓
HTTP
   ↓
Server
   ↓
Response
   ↓
Browser
```

Networking knowledge is particularly valuable for cloud, cybersecurity, backend engineering, and distributed systems.

---

# 🌍 Distributed Systems

A distributed system consists of multiple computers communicating and working together.

### Learn

- Processes
- Communication
- Replication
- Consistency
- Availability
- Fault tolerance
- Consensus
- Partitioning
- Load balancing
- Distributed storage
- Distributed databases
- Messaging

### Important Concepts

- CAP theorem
- Consensus
- Leader election
- Replication
- Sharding
- Eventual consistency
- Distributed transactions
- Fault tolerance

Distributed systems become increasingly important as applications grow.

---

# ⚙️ Systems Programming

Systems programming involves building software that interacts closely with operating systems and hardware.

### Common Languages

- C
- C++
- Rust
- Assembly

### Examples

- Operating system components
- Compilers
- Device drivers
- Network software
- Databases
- Runtime systems
- System utilities
- Performance-critical software

C is especially useful for understanding memory, pointers, processes, and low-level programming.

---

# 🔌 Embedded Systems

Embedded systems are computing systems designed as part of a larger physical device.

Examples include:

- Microcontrollers
- Automotive systems
- IoT devices
- Robotics
- Industrial controllers
- Consumer electronics

### Learn

- Microcontrollers
- GPIO
- Timers
- Interrupts
- Sensors
- Communication protocols
- Memory
- Real-time systems
- Embedded C/C++
- Hardware interfaces

### Common Technologies

- Arduino
- ESP32
- STM32
- ARM
- Raspberry Pi
- FreeRTOS

---

# 🧱 Foundations

A useful systems foundation includes:

- C programming
- Data Structures
- Algorithms
- Computer Architecture
- Operating Systems
- Computer Networks
- Linux
- Discrete Mathematics

You do not need to master all of these before starting.

Start with one area and gradually connect it to the others.

---

# 🐧 Linux

Linux is particularly important when studying systems, cloud, networking, and cybersecurity.

### Basic

Learn:

- Filesystem
- Commands
- Permissions
- Users
- Groups
- Processes
- Packages

### Intermediate

Learn:

- Shell scripting
- Services
- Logs
- Environment variables
- SSH
- Networking
- Process management

### Advanced

Explore:

- System calls
- Kernel concepts
- Filesystems
- Scheduling
- Memory
- Kernel modules

---

# 🧵 Concurrency

Concurrency is fundamental to operating systems and modern software.

### Learn

- Processes
- Threads
- Race conditions
- Critical sections
- Mutexes
- Semaphores
- Monitors
- Deadlocks
- Synchronization

### Basic Idea

```text
Multiple Threads
      │
      ↓
 Shared Resources
      │
      ↓
Synchronization
      │
      ↓
Correct Program
```

---

# ⚡ Performance

Systems engineers often need to understand why software is slow.

### Learn

- CPU utilization
- Memory usage
- I/O
- Latency
- Throughput
- Caching
- Profiling
- Benchmarking
- Algorithmic complexity

### Practical Approach

```text
Measure
  ↓
Find the bottleneck
  ↓
Understand the cause
  ↓
Optimize
  ↓
Measure again
```

Don't optimize based only on assumptions.

---

# 🛠️ Important Tools

## Linux

- Bash
- SSH
- systemd
- grep
- sed
- awk
- ps
- top
- htop
- lsof

## Networking

- ping
- traceroute
- curl
- wget
- ss
- dig
- nslookup
- tcpdump
- Wireshark

## Development

- GCC
- GDB
- Make
- CMake
- Git

## Performance & Debugging

- perf
- Valgrind
- strace
- GDB

Learn the purpose of a tool before memorizing its commands.

---

# 🧪 Projects

## Beginner

### 1. Linux Command-Line Utility

Build a small utility using C or Python.

### 2. Mini Shell

Build a simple shell that can:

- Execute commands
- Accept arguments
- Handle basic built-in commands
- Create processes

### 3. TCP Client and Server

Build a simple client-server application using TCP.

---

## Intermediate

### 4. Multithreaded Application

Build an application using multiple threads and synchronization.

### 5. HTTP Server

Build a basic HTTP server.

Understand:

```text
TCP Connection
      ↓
HTTP Request
      ↓
Request Parsing
      ↓
Application Logic
      ↓
HTTP Response
```

### 6. File System Project

Build a simplified file storage system or explore the design of an existing filesystem.

---

## Advanced

### 7. OS Experiment

Experiment with:

- Process creation
- Scheduling
- Memory management
- System calls

### 8. Distributed Key-Value Store

Build a small distributed storage system.

Explore:

- Replication
- Communication
- Failure
- Consistency

### 9. Multi-Client Network Server

Build a network server capable of handling multiple clients concurrently.

### 10. Embedded System

Build a microcontroller project involving:

- Sensors
- Interrupts
- Communication
- Real-time behaviour

---

# 🛣️ Practical Learning Path

```text
C Programming
      ↓
Linux
      ↓
Computer Architecture
      ↓
Operating Systems
      ↓
Computer Networks
      ↓
Concurrency
      ↓
Systems Programming
      ↓
Choose a direction
      │
      ├── Systems Software
      ├── Networking
      ├── Distributed Systems
      ├── Cloud
      ├── Cybersecurity
      └── Embedded Systems
```

This is a flexible learning path, not a strict requirement.

---

# 📚 Resources

The resources below are selected for different purposes: explanations, textbooks, official documentation, and hands-on learning.

---

# 🧠 Computer Architecture

### GeeksforGeeks — Computer Organization and Architecture

Useful explanations covering CPU, memory, cache, instruction sets, pipelining, and related concepts.

https://www.geeksforgeeks.org/computer-organization-and-architecture-tutorials/

### Nand2Tetris

A hands-on course where you progressively build a computer system from basic logic gates.

https://www.nand2tetris.org/

This is excellent if you want to understand how hardware and software connect.

---

# 🖥️ Operating Systems

### GeeksforGeeks — Operating Systems

Large collection covering processes, threads, scheduling, memory management, deadlocks, file systems, and other OS concepts.

https://www.geeksforgeeks.org/operating-systems/

### Operating Systems: Three Easy Pieces

A free online textbook covering virtualization, concurrency, and persistence.

https://pages.cs.wisc.edu/~remzi/OSTEP/

### MIT Operating Systems — xv6

Hands-on operating systems course material based around xv6.

https://pdos.csail.mit.edu/6.1810/

Use this after understanding basic OS concepts.

---

# 🌐 Computer Networks

### GeeksforGeeks — Computer Networks

Useful explanations and practice material for networking fundamentals.

https://www.geeksforgeeks.org/computer-networks/

### Computer Networking: A Top-Down Approach

A widely used networking resource that explains networking from the application layer downward.

https://gaia.cs.umass.edu/kurose_ross/

### Wireshark

Use packet captures to observe networking concepts rather than learning them only theoretically.

https://www.wireshark.org/

---

# 🌍 Distributed Systems

### MIT 6.5840

Hands-on distributed systems course involving distributed programming and fault-tolerant systems.

https://pdos.csail.mit.edu/6.824/

### Designing Data-Intensive Applications

A major resource for understanding distributed systems, storage, databases, replication, and data-intensive architecture.

https://dataintensive.net/

### GeeksforGeeks — Distributed Systems

Useful supplementary explanations for distributed computing concepts.

https://www.geeksforgeeks.org/system-design/distributed-systems-tutorial/

---

# 🐧 Linux

### Linux Journey

Interactive Linux learning material.

https://linuxjourney.com/

### Linux Documentation

Official Linux documentation.

https://www.kernel.org/doc/

### The Linux Command Line

A practical book for learning the command line and shell concepts.

https://linuxcommand.org/tlcl.php

### GeeksforGeeks — Linux

Useful supplementary tutorials and command references.

https://www.geeksforgeeks.org/linux-unix/

---

# ⚙️ C Programming

### GeeksforGeeks — C Programming

Tutorials, examples, and practice material.

https://www.geeksforgeeks.org/c-programming-language/

### cppreference — C

Useful reference for the C language and standard library.

https://en.cppreference.com/w/c

### Beej's Guide to C Programming

A practical guide for learning C.

https://beej.us/guide/bgc/

---

# 🦀 Rust

### The Rust Book

Official Rust programming language book.

https://doc.rust-lang.org/book/

Rust is particularly interesting for systems programming because it combines low-level control with strong memory-safety guarantees.

---

# 🐞 Debugging

### GDB Documentation

Official documentation for the GNU debugger.

https://sourceware.org/gdb/documentation/

### Valgrind

Tools for debugging and profiling programs, including memory-related problems.

https://valgrind.org/

### strace

Useful for observing system calls and signals made by programs.

https://strace.io/

---

# 🌐 Networking Tools

### Nmap

Network discovery and security auditing tool.

https://nmap.org/

### tcpdump

Command-line packet capture and analysis tool.

https://www.tcpdump.org/

### Wireshark

Graphical network protocol analyzer.

https://www.wireshark.org/

---

# 🔧 Build Systems

### CMake

Cross-platform build system commonly used for C and C++ projects.

https://cmake.org/documentation/

### GNU Make

Build automation tool commonly used in systems projects.

https://www.gnu.org/software/make/manual/

---

# 🔌 Embedded Systems

### Arduino Documentation

https://docs.arduino.cc/

### ESP32 Documentation

Official documentation for ESP32 development.

https://docs.espressif.com/projects/esp-idf/en/latest/esp32/

### STM32

Official STM32 development resources and documentation.

https://www.st.com/en/microcontrollers-microprocessors/stm32-32-bit-arm-cortex-mcus.html

### FreeRTOS

Real-time operating system for microcontrollers and embedded systems.

https://www.freertos.org/

---

# 🧪 Hands-On Learning

Systems knowledge becomes much stronger when you experiment.

Use this cycle:

```text
Learn a concept
      ↓
Write a small program
      ↓
Run it
      ↓
Observe what the OS does
      ↓
Inspect processes / memory / network
      ↓
Modify the program
      ↓
Measure the result
```

For example:

```text
Learn Processes
      ↓
Write a C program
      ↓
Use fork()
      ↓
Observe processes using Linux tools
      ↓
Inspect process IDs
      ↓
Understand parent / child processes
```

---

# 🧪 Practice Ideas

Try experiments such as:

### Process Experiment

Create multiple processes and observe them using:

- ps
- top
- htop

### Network Experiment

Create a TCP client and server and observe the traffic using Wireshark.

### Memory Experiment

Write a C program containing different types of variables and use a debugger to inspect memory.

### Linux Experiment

Create users, groups, permissions, processes, services, and shell scripts.

### Performance Experiment

Write two versions of a program and benchmark them.

The goal is to turn concepts into observable behaviour.

---

# 🔗 Connections With Other Fields

```text
                 Systems
                /   |   \
               /    |    \
             OS   Networks  Architecture
              \      |      /
               \     |     /
                Distributed
                   Systems
                      │
             ┌────────┼────────┐
             ↓        ↓        ↓
           Cloud   Security   Backend
             │        │        │
             └────────┼────────┘
                      ↓
                Large Systems
```

Systems knowledge connects strongly with:

- Cloud Engineering
- DevOps
- Cybersecurity
- Backend Engineering
- Distributed Systems
- Embedded Systems
- Performance Engineering
- Database Engineering

---

# 🎯 How to Explore Systems

If you're completely new:

```text
C
 ↓
Linux
 ↓
Computer Architecture
 ↓
Operating Systems
 ↓
Networking
 ↓
Concurrency
 ↓
Build Something
 ↓
Choose a specialization
```

Don't try to learn the entire systems field at once.

Pick one concept and make it tangible through code or experiments.

---

# ⚠️ Why Systems Can Feel Difficult

Systems concepts can initially feel difficult because you are learning what happens underneath the abstractions used by everyday applications.

For example:

```text
Application
     ↓
Programming Language
     ↓
Compiler / Runtime
     ↓
Operating System
     ↓
CPU / Memory
     ↓
Hardware
```

Understanding these layers gradually makes many "mysterious" computer behaviours much easier to reason about.

---

# 🧭 Where Systems Can Lead

```text
Systems & Core Computing
│
├── Systems Software Engineer
│
├── Operating Systems
│
├── Network Engineer
│
├── Distributed Systems Engineer
│
├── Infrastructure Engineer
│
├── Performance Engineer
│
├── Embedded Engineer
│
├── Kernel / Driver Development
│
└── Security Engineering
```

Actual job titles and responsibilities vary between organizations.

---

# 🚀 A Good Way to Start

If this field interests you, don't begin by trying to learn everything.

Pick one small question:

> "What actually happens when I run a C program?"

Then explore:

```text
C Program
   ↓
Compiler
   ↓
Executable
   ↓
Operating System
   ↓
Process
   ↓
Memory
   ↓
CPU
```

That single question can lead you into a large part of Computer Science.

---

**`cd CSE` → go beneath the application layer, understand how computers actually work, and build from the fundamentals.**