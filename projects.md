# 🚀 My Projects

Welcome to my project portfolio. Here you will find a detailed list of the projects I have completed. Each project is a step forward in my journey as a software engineer.

---

## 📚 Libft
* **What it does:** A comprehensive custom C library. It contains reimplementations of many functions from the standard library (`<string.h>`, `<stdlib.h>`, etc.) as well as additional useful functions for linked lists.
* **Why I built it:** It taught me the fundamentals of the C language, memory management, and the importance of creating robust and well-documented code. It forced me to understand what happens "under the hood" of standard functions.
* **How to compile & run:**
    -  `git clone git@github.com:carlopezc/Libft.git`
    -  `cd libft`
    -  `make`
    -  This creates a `libft.a` file to be linked with other projects.
* **Repository:** https://github.com/carlopezc/Libft

---

##  📥 Get Next Line
* **What it does:** A function that reads a file line by line. It's efficient because it uses a static buffer to minimize `read()` calls.
* **Why I built it:** This project is a deep dive into static variables, file descriptors, and memory management. It's a classic challenge that taught me how to handle persistent data between function calls.
* **How to compile & run:**
    -  `git clone git@github.com:carlopezc/Get_next_line.git`
    -  Include `get_next_line.c` and its related files in your project.
    -  Compile with your other `.c` files (e.g., `gcc main.c get_next_line.c`).
    -  Call the `get_next_line()` function in a loop.
* **Repository:** https://github.com/carlopezc/Get_next_line

---

## 🖨️ ft_printf
* **What it does:** A complete recreation of the standard C `printf` function, handling various flags (`c, s, p, d, i, u, x, X, %`).
* **Why I built it:** To master variadic functions, a powerful but complex feature of C. This project significantly improved my skills in argument handling, string manipulation, and modular code design.
* **How to compile & run:**
    -  `git clone git@github.com:carlopezc/Printf.git`
    -  `cd ft_printf`
    -  `make` (this will create a `libftprintf.a` library).
    -  Link the library when compiling your main program: `gcc your_program.c -L. -lftprintf`.
* **Repository:** https://github.com/carlopezc/Printf

---

## 🐧 Born2BeRoot
* **What it does:** A system administration project involving the setup of a secure Debian server on a virtual machine.
* **Why I built it:** This was my introduction to the world of system administration and security. I learned about partitioning, SSH, firewalls (UFW), user management, and cron jobs. It taught me that software needs a secure and stable environment to run on.

---

## 🔄 Push Swap
* **What it does:** An algorithm that sorts a stack of numbers using a limited set of instructions, aiming for the lowest possible move count.
* **Why I built it:** This project is a pure algorithmic challenge. It forced me to analyze complexities, design an efficient sorting strategy (based on radix sort or similar concepts), and optimize every instruction.
* **How to compile & run:**
    -  `git clone git@github.com:carlopezc/Push_swap.git`
    -  `make`
    -  `./push_swap [list of numbers]` (e.g., `./push_swap 4 67 3 8 2`).
* **Repository:** https://github.com/carlopezc/Push_swap

---

## 🕹️ Pipex
* **What it does:** A program that mimics the behavior of the shell pipe (`|`). For example: `< file1 cmd1 | cmd2 > file2`.
* **Why I built it:** To understand how commands are executed and how they communicate in a UNIX-like environment. I learned about process creation (`fork`), execution (`execve`), and inter-process communication using `pipe()`.
* **How to compile & run:**
    -  `git clone git@github.com:carlopezc/Pipex.git`
    -  `make`
    -  `./pipex infile "cmd1" "cmd2" outfile`.
* **Repository:** https://github.com/carlopezc/Pipex

---

## 🌐 FdF (Fil de Fer)
* **What it does:** A program that reads a map of 3D coordinates (x, y, z for altitude) from a file and renders a 2D isometric (wireframe) projection, creating a 3D-like landscape on the screen.
* **Why I built it:** This was my first foray into graphics programming using the MiniLibX library. It was a fantastic practical exercise in applying mathematical concepts, specifically linear algebra for transformations like rotation, translation, and scaling. I learned to manage a graphical window and handle user input (keyboard events) for an interactive experience.
* **How to compile & run:**
    -  `git clone git@github.com:carlopezc/Fdf.git`
    -  `make`
    -  `./fdf [path_to_map_file]` (e.g., `./fdf maps/pylone.fdf`).
    -  Use keyboard controls (e.g., arrows to move, +/- to zoom, R to rotate) to interact with the model.
* **Repository:** https://github.com/carlopezc/Fdf

---

## 🐚 MiniShell
* **What it does:** A custom-built shell that can parse and execute commands, manage environment variables, handle signals (`Ctrl-C`, `Ctrl-\`), and implement I/O redirections (`>`, `<`, `>>`, `<<`) and pipes (`|`).
* **Why I built it:** This is a major project that ties together many concepts of system programming. It was a huge challenge in parsing, process management, and state handling. It's the project I'm proudest of for its complexity.
* **How to compile & run:**
    -  `git clone git@github.com:carlopezc/Minishell.git`
    -  `make`
    -  `./minishell`.
* **Repository:** https://github.com/carlopezc/Minishell/tree/new_version

---

## 🍽️ Philosophers
* **What it does:** A simulation of the "Dining Philosophers" problem, a classic concurrency challenge. It uses threads and mutexes to prevent deadlocks and data races.
* **Why I built it:** To dive into the world of multithreading. I learned the critical importance of synchronization, how to use mutexes to protect shared resources, and how to design a program that avoids common concurrency issues like deadlocks.
* **How to compile & run:**
    -  `git clone git@github.com:carlopezc/Philosophers.git`
    -  `make`
    -  `./philo [number_of_philosophers] [time_to_die] [time_to_eat] [time_to_sleep] [optional: number_of_meals]`.
* **Repository:** https://github.com/carlopezc/Philosophers

---
