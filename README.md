# Mini_Operating_System
# OS Task Execution System (Multithreaded Simulation)

This project simulates an operating system interface where users can select and execute various predefined tasks such as calculator, calendar, clock, games, and utilities. It uses C++ with POSIX threads (`pthreads`) to handle task execution and provides a user-friendly menu-based interface.

## Features

- Simulates a basic OS task selector
- Executes each task in a new terminal window
- Tasks are compiled and run dynamically
- Uses multithreading with `pthreads` for parallel task execution
- Simulates resource allocation checks (e.g., CPU availability)

## Tasks Included

1. Calculator  
2. Calendar  
3. Clock  
4. Snake Game  
5. Tic Tac Toe  
6. File Encryption  
7. File Decryption  
8. Memory Viewer  
9. CPU Monitor  
10. Weather App  
11. Notes  
12. Alarm Clock  
13. Stopwatch  

## Prerequisites

- Linux OS (tested on Ubuntu)
- `g++` compiler
- `x-terminal-emulator` or compatible terminal (e.g., GNOME Terminal, xterm)
- POSIX thread library (`-pthread`)

## Compilation

Compile the main program using:

```bash
g++ main.cpp -o main -pthread
