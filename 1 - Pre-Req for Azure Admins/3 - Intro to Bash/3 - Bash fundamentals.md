# 3 - Bash Fundamentals

## 🎯 Goal:
Learn the basic syntax and functionality of Bash commands, including how to list directory contents, use command options, access help documentation, and work with wildcards for pattern matching.

## 🧠 1. Break it Down

### ![#f03c15](https://placehold.co/15x15/f03c15/f03c15.png) **Important**
- **Bash Command Structure**: A typical Bash command follows this structure: `command [options] [arguments]`.
- **Listing Directory Contents**: The `ls` command lists files and directories.
  - `ls` - Lists files in the current directory.
  - `ls /path/to/directory` - Lists files in a specified directory.
  - `ls -a /path/to/directory` - Includes hidden files (files starting with a dot).
  - `ls -al /path/to/directory` - Combines multiple options for a detailed listing.
- **Accessing Help Documentation**:
  - Use `man command_name` to view the manual page for a command.
  - Use `command_name --help` for a concise summary of command usage.
- **Using Wildcards**:
  - `*` matches zero or more characters. Example: `ls *.txt` lists all `.txt` files.
  - `?` matches a single character. Example: `ls file?.txt` matches `file1.txt`, `file2.txt`, etc.
  - `[]` defines a range or set of characters. Example: `ls file[1-3].txt` matches `file1.txt`, `file2.txt`, and `file3.txt`.

### ![#c5f015](https://placehold.co/15x15/c5f015/c5f015.png) **Key Features**
- **Command Options**: Modify command behavior using flags (e.g., `-a`, `-l`).
- **Help System**: Access detailed command information using `man` pages or quick help via `--help`.
- **Pattern Matching**: Use wildcards to search for files and directories matching specific patterns.

### ![#f0e15d](https://placehold.co/15x15/f0e15d/f0e15d.png) **Supporting Details/Examples**
- **Combining Options**: Use combined options for customized output, e.g., `ls -al` for a detailed listing with hidden files.
- **Help Documentation**: Use `mkdir --help` to get usage details for the `mkdir` command.
- **Advanced Pattern Matching**: Use wildcards like `ls file[1-9].*` to list files that start with 'file' and are followed by a number.

## 🔍 2. Summary
Bash commands are structured with a command, followed by options and arguments, which allows users to manage and navigate the system efficiently.

## 🔥 3. Analogy
Bash is like a sophisticated search engine for your computer. Just as you enter specific keywords to find information online, you use specific commands and options in Bash to find, manage, and manipulate files on your system.
