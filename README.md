# ✍️ Minishell - 42 School Project
# 🌟 Overview
    Minishell is a C programming project from the 42 School curriculum. It involves building a simplified UNIX shell from scratch, capable of executing commands, handling input/output, and managing basic shell features. This repository contains two implementations:
    Mandatory Part: A functional shell with basic command execution, pipes, and built-ins.
    Bonus Part: Extends the shell with additional features like advanced redirections and wildcard support. The goal is to replicate core shell behavior without relying on external libraries beyond standard C: $> ./minishell

# ✨ Features
    Mandatory:
        Executes simple commands (e.g., ls -l, cat file.txt).
        Supports pipes (|).
        Built-ins: echo, cd, pwd, export, unset, env, exit.
        Handles environment variables and signal management (e.g., Ctrl+C).
    Bonus:
        Advanced redirections (>>, << heredoc).
        Wildcard expansion (e.g., ls *.txt).
        Logical operators (&&, ||) for command chaining.
    Common Features:
        Command parsing and error handling.
        Interactive prompt with command history.

# 🚀 Installation
    Clone the repo:
      git clone https://github.com/b-kolani/minishell.git
    Enter the directory:
      cd minishell
    Compile:
      make will compile both parts mandatory and bonus.

# 🖥️ Usage
    Execute ./minishell this will propmt for command:
    Example:
      Minishell $> echo "Hello" | cat -e
      Minishell $> ls *.c > out.txt && cat out.txt
    Run the shell and type commands as you would in bash. Exit with exit or Ctrl+D.

# 📂 Project Structure
    minishell.c Main function and core logic for the mandatory part
    Makefile Build rules for both mandatory and bonus targets

# 🎓 Learning Outcomes
    Mandatory: Mastered process creation (fork/exec), pipe management, and signal handling.
    Bonus: Gained expertise in parsing complex input, implementing redirections, and handling wildcards.
    Deepened understanding of UNIX systems, environment variables, and shell mechanics.
    Improved skills in string manipulation, memory management, and error handling.

# ⚙️ Requirements
    OS: UNIX-based (Linux, macOS).
    Compiler: GCC or similar.
    Standard C libraries.

# 👤 Author
    [KOlani Biman / b-kolani]
