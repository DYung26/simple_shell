# 0x16. C - Simple Shell

## Simple Shell Implementation in C

## Overview

This project, titled "0x16. C - Simple Shell," is an implementation of a basic shell in the C programming language. The shell provides a command-line interface, allowing users to interact with the underlying operating system by executing commands.

## Features

- **Command Execution:** The shell can execute a variety of commands, including built-in commands and external executable files.

- **Built-in Commands:** The shell supports essential built-in commands such as `exit`, `cd`, `env`, `help`, `history`, `setenv`, `unsetenv`, `alias`, and more.

- **Command Chaining:** Users can chain commands together using delimiters like `;`, `&&`, and `||`.

- **Environment Variable Handling:** The shell manages environment variables and allows users to interact with them using commands like `setenv` and `unsetenv`.

- **History Functionality:** The shell maintains a command history, allowing users to review and repeat previous commands.

## Getting Started

To use this simple shell:

1. **Compilation:** Compile the source code using a C compiler (e.g., GCC).
   ```bash
   gcc -o simple_shell *.c
2. **Run the Shell:**
    ```bash
    ./simple_shell
3. **Interactive Mode:**
    The shell provides an interactive command-line interface, accepting user commands.
4. **Command Execution:**
    Execute commands as you would in a typical shell, including built-in commands and external executables.

## Project Structure

- **Source Files:** The C source code is organized into multiple files, each responsible for specific functionalities such as command execution, parsing, string manipulation, and more.

- **Header Files:** The shell.h header file contains necessary declarations and macro definitions used across the project.

- **Utility Functions:** Various utility functions enhance the shell's capabilities, providing features like string manipulation, tokenization, and memory management.

## Contributions

Contributions to the project are welcome. Feel free to submit bug reports, suggest enhancements, or contribute new features. Follow common conventions and create descriptive commit messages.

## License

This simple shell project is open-source and distributed under the MIT License. You are free to use, modify, and distribute the code for both personal and commercial purposes.