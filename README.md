# To-Do List (using C)

**A lightweight, file-based task manager built with pure C.**

-----

## 📖 Overview

This is a minimalist console-based application designed for efficiency. It allows users to manage their daily tasks directly from the terminal. Unlike basic programs that lose data on exit, this version uses **File I/O** to ensure your tasks are saved and reloaded every time you run the app.

-----

## 🛠 Features

  * **Task Persistence:** Automatically saves tasks to a `.txt` or `.dat` file.
  * **Dynamic Management:** Add, view, and remove tasks during runtime.
  * **Memory Efficient:** Uses optimized data structures (like `structs`) for task handling.
  * **Clean Interface:** Simple numeric menu for easy navigation.

-----

## 🧱 Tech Stack

| Component | Technology |
| :--- | :--- |
| **Language** | C (C11/C17) |
| **Libraries** | `stdio.h`, `stdlib.h`, `string.h` |
| **Storage** | Flat File System (`tasks.txt`) |

-----

## 🚀 Getting Started

### 1\. Prerequisites

You need a C compiler installed (like **GCC**).

### 2\. Compilation

Open your terminal and run:

```bash
gcc main.c -o todo
```

### 3\. Execution

Run the compiled program:

```bash
./todo
```

-----

## 📂 Project Logic

The project is structured around a central `Task` structure:

```c
struct Task {
    int id;
    char description[100];
    int is_completed;
};
```

-----

## 🤝 Contributing

1.  **Fork** the repository.
2.  Create a **Branch** for your feature.
3.  Submit a **Pull Request** for review.

**Author:**

[Stella Saji]

(https://www.google.com/search?q=https://github.com/stella-saji)  
**License:** MIT

-----
