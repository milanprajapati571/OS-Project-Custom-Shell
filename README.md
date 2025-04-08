# 🐚 Custom Shell - Operating Systems Project

This project is a **custom-built shell** developed as part of our Operating Systems course at IIT (ISM) Dhanbad. The shell is designed to interpret and execute user commands similarly to traditional Unix shells.

## 🎯 Features

- Basic command execution (`ls`, `cd`, `mkdir`, `rm`, etc.)
- Background process execution using `&`
- Command history management
- Input/output redirection (`<`, `>`, `>>`)
- Piping (`|`)
- Built-in commands (`cd`, `exit`, etc.)
- Signal handling (e.g., `Ctrl+C`)
- Error handling and informative messages

## ⚙️ How It Works

The shell:
1. Displays a prompt and waits for user input.
2. Parses the input and identifies commands, arguments, and operators.
3. Executes built-in commands internally.
4. Forks child processes for external commands.
5. Handles redirection, background execution, and piping using system calls.

## 🛠️ Technologies Used

- **Language**: C
- **System Calls**: `fork()`, `execvp()`, `waitpid()`, `dup2()`, etc.
- **OS Concepts**: Process creation, file descriptors, signal handling

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/milanprajapati571/OS-Project-Custom-Shell.git
   cd OS-Project-Custom-Shell
