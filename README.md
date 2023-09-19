# Simple Shell Project in C

This is a simple shell project implemented in C for the ALX Software Engineering program. The project provides a basic shell environment with various built-in functions and utilities. The project is organized into multiple source code files, each containing specific functions and functionalities.

## Table of Contents

- [Source Code Files](#source-code-files)
  - [`atoi.c`](#atoi.c)
  - [`builtin.c`](#builtin.c)
  - [`builtin1.c`](#builtin1.c)
  - [`environ.c`](#environ.c)
  - [`errors.c`](#errors.c)
  - [`errors1.c`](#errors1.c)
  - [`exits.c`](#exits.c)
  - [`getLine.c`](#getLine.c)
  - [`getenv.c`](#getenv.c)
  - [`getinfo.c`](#getinfo.c)
  - [`history.c`](#history.c)
  - [`lists.c`](#lists.c)
  - [`lists1.c`](#lists1.c)
  - [`main.c`](#main.c)
  - [`memory.c`](#memory.c)
  - [`parser.c`](#parser.c)
- [How to Compile and Run](#how-to-compile-and-run)
- [Usage](#usage)
- [Authors](#authors)

## Source Code Files

### `atoi.c`
- `interactive`: Functions for handling interactive mode.
- `is_delim`: Checks if a character is a delimiter.
- `_isalpha`: Checks if a character is alphabetic.
- `_atoi`: Converts a string to an integer.

### `builtin.c`
- `_myexit`: Implements the exit built-in command.
- `_mycd`: Implements the cd (change directory) built-in command.
- `_myhelp`: Implements the help built-in command.

### `builtin1.c`
- `_myhistory`: Implements the history built-in command.
- `unset_alias`: Unsets an alias.
- `set_alias`: Sets an alias.
- `print_alias`: Prints defined aliases.
- `_myalias`: Implements the alias built-in command.

### `environ.c`
- `_myenv`: Prints the environment variables.
- `_getenv`: Gets the value of an environment variable.
- `_mysetenv`: Sets an environment variable.
- `_myunsetenv`: Unsets an environment variable.
- `populate_env_list`: Populates the environment variable list.

### `errors.c`
- `_eputs`: Prints an error message.
- `_eputchar`: Prints an error character.
- `_putfd`: Writes to a file descriptor.
- `_putsfd`: Writes a string to a file descriptor.

### `errors1.c`
- `_erratoi`: Handles errors during string to integer conversion.
- `print_error`: Prints an error message.
- `print_d`: Prints an integer.
- `convert_number`: Converts a string to a number.
- `remove_comments`: Removes comments from input.

### `exits.c`
- `_strncpy`: Copies a string up to a specified length.
- `_strncat`: Concatenates two strings up to a specified length.
- `_strchr`: Locates the first occurrence of a character in a string.

### `getLine.c`
- `input_buf`: Handles input buffer.
- `get_input`: Reads user input.
- `read_buf`: Reads from the input buffer.
- `_getline`: Reads a line from the input.
- `sigintHandler`: Handles Ctrl+C interrupts.

### `getenv.c`
- `get_environ`: Gets the environment variable list.
- `_unsetenv`: Unsets an environment variable.
- `_setenv`: Sets an environment variable.

### `getinfo.c`
- `clear_info`: Clears the command info structure.
- `set_info`: Sets the command info.
- `free_info`: Frees memory associated with the command info.

### `history.c`
- `get_history_file`: Gets the history file path.
- `write_history`: Writes command history to a file.
- `read_history`: Reads command history from a file.
- `build_history_list`: Builds a linked list of command history.
- `renumber_history`: Renumbers the command history.

### `lists.c`
- `add_node`: Adds a node to a linked list.
- `add_node_end`: Adds a node to the end of a linked list.
- `print_list_str`: Prints a linked list of strings.
- `delete_node_at_index`: Deletes a node at a specific index.
- `free_list`: Frees memory associated with a linked list.

### `lists1.c`
- `list_len`: Gets the length of a linked list.
- `list_to_strings`: Converts a linked list to an array of strings.
- `print_list`: Prints a linked list.
- `node_starts_with`: Checks if a node starts with a specific string.
- `get_node_index`: Gets the index of a node in a linked list.

### `main.c`
- `main`: The main function of the shell program.

### `memory.c`
- `bfree`: Frees allocated memory.

### `parser.c`
- `is_cmd`: Checks if a string is a command.
- `dup_chars`: Duplicates a string.
- `find_path`: Finds the executable path of a command.

## How to Compile and Run

To compile and run the simple shell project, you can use the following steps:

1. Clone the repository:
   ```shell
   git clone https://github.com/nanakwasi-0/simple_shell
   cd simple_shell
   gcc -std=gnu89 -o myshell *.c && ./myshell
## Usage

Once the shell is running, you can use various built-in commands and execute other programs. Use the help command to display available commands and their descriptions.

## Authors

Nana Owusu

Kelvin Carrington Tichana
