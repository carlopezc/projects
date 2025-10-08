# 🚀 My Projects

Welcome to my project portfolio. Here you will find a detailed list of the projects I have completed. Each project is a step forward in my journey as a software engineer.

---

## 📚 Libft
* **What it does:** A comprehensive custom C library. It contains reimplementations of many functions from the standard library (`<string.h>`, `<stdlib.h>`, etc.) as well as additional useful functions for linked lists.
* **Why I built it:** It taught me the fundamentals of the C language, memory management, and the importance of creating robust and well-documented code. It forced me to understand what happens "under the hood" of standard functions.
* **How to compile & run:**
    1.  `git clone [your-repo-url]`
    2.  `cd libft`
    3.  `make`
    4.  This creates a `libft.a` file to be linked with other projects.
* **Repository:** `[GitHub Link](https://github.com/carlopezc/your-libft-repo)`

---

##  📥 Get Next Line
* **What it does:** A function that reads a file line by line. It's efficient because it uses a static buffer to minimize `read()` calls.
* **Why I built it:** This project is a deep dive into static variables, file descriptors, and memory management. It's a classic challenge that taught me how to handle persistent data between function calls.
* **How to compile & run:**
    1.  Include `get_next_line.c` and its related files in your project.
    2.  Compile with your other `.c` files (e.g., `gcc main.c get_next_line.c`).
    3.  Call the `get_next_line()` function in a loop.
* **Repository:** `[GitHub Link](https://github.com/carlopezc/your-gnl-repo)`

---

## 🖨️ ft_printf
* **What it does:** A complete recreation of the standard C `printf` function, handling various flags (`c, s, p, d, i, u, x, X, %`).
* **Why I built it:** To master variadic functions, a powerful but complex feature of C. This project significantly improved my skills in argument handling, string manipulation, and modular code design.
* **How to compile & run:**
    1.  `git clone [your-repo-url]`
    2.  `cd ft_printf`
    3.  `make` (this will create a `libftprintf.a` library).
    4.  Link the library when compiling your main program: `gcc your_program.c -L. -lftprintf`.
* **Repository:** `[GitHub Link](https://github.com/carlopezc/your-printf-repo)`

---

## 🐧 Born2BeRoot
* **What it does:** A system administration project involving the setup of a secure Debian server on a virtual machine.
* **Why I built it:** This was my introduction to the world of system administration and security. I learned about partitioning, SSH, firewalls (UFW), user management, and cron jobs. It taught me that software needs a secure and stable environment to run on.
* **How to compile & run:** This project is a set of configuration steps, not a program to compile. The repository contains a summary of the setup and security measures implemented.
* **Repository:** `[GitHub Link](https://github.com/carlopezc/your-born2beroot-repo)`

---

## 🔄 Push Swap
* **What it does:** An algorithm that sorts a stack of numbers using a limited set of instructions, aiming for the lowest possible move count.
* **Why I built it:** This project is a pure algorithmic challenge. It forced me to analyze complexities, design an efficient sorting strategy (based on radix sort or similar concepts), and optimize every instruction.
* **How to compile & run:**
    1.  `make`
    2.  `./push_swap [list of numbers]` (e.g., `./push_swap 4 67 3 8 2`).
* **Repository:** `[GitHub Link](https://github.com/carlopezc/your-push-swap-repo)`

---

## 🕹️ Pipex
* **What it does:** A program that mimics the behavior of the shell pipe (`|`). For example: `< file1 cmd1 | cmd2 > file2`.
* **Why I built it:** To understand how commands are executed and how they communicate in a UNIX-like environment. I learned about process creation (`fork`), execution (`execve`), and inter-process communication using `pipe()`.
* **How to compile & run:**
    1.  `make`
    2.  `./pipex infile "cmd1" "cmd2" outfile`.
* **Repository:** `[GitHub Link](https://github.com/carlopezc/your-pipex-repo)`

---

## 🐚 MiniShell
* **What it does:** A custom-built shell that can parse and execute commands, manage environment variables, handle signals (`Ctrl-C`, `Ctrl-\`), and implement I/O redirections (`>`, `<`, `>>`, `<<`) and pipes (`|`).
* **Why I built it:** This is a major project that ties together many concepts of system programming. It was a huge challenge in parsing, process management, and state handling. It's the project I'm proudest of for its complexity.
* **How to compile & run:**
    1.  `make`
    2.  `./minishell`.
* **Repository:** `[GitHub Link](https://github.com/carlopezc/your-minishell-repo)`

---

## 🍽️ Philosophers
* **What it does:** A simulation of the "Dining Philosophers" problem, a classic concurrency challenge. It uses threads and mutexes to prevent deadlocks and data races.
* **Why I built it:** To dive into the world of multithreading. I learned the critical importance of synchronization, how to use mutexes to protect shared resources, and how to design a program that avoids common concurrency issues like deadlocks.
* **How to compile & run:**
    1.  `make`
    2.  `./philo [number_of_philosophers] [time_to_die] [time_to_eat] [time_to_sleep] [optional: number_of_meals]`.
* **Repository:** `[GitHub Link](https://github.com/carlopezc/your-philosophers-repo)`

---
