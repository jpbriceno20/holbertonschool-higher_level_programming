# Python - Import & Modules

This project is part of the Holberton School Higher Level Programming track. It covers how to import modules, use functions across files, handle command line arguments, and control script behavior when imported.

## Learning Objectives

- Why Python programming is powerful and flexible
- How to import functions from another file
- How to use imported functions
- How to create your own Python modules
- How to use the built-in `dir()` function
- How to prevent code from running when a script is imported
- How to use command line arguments with `sys.argv`

## Requirements

- Python 3.10 on Ubuntu 22.04
- All scripts must start with `#!/usr/bin/python3`
- All files must be executable
- Code must follow `pycodestyle` (version 2.7.*)
- No wildcard `*` or `__import__` allowed
- Each file must end with a new line

## Project Files

| File                  | Description                                                |
|-----------------------|------------------------------------------------------------|
| `0-add.py`            | Imports a function and prints the result of `1 + 2`        |
| `1-calculation.py`    | Imports multiple math functions and prints their results   |
| `2-args.py`           | Prints number of arguments and lists them from `sys.argv`  |
| `3-infinite_add.py`   | Adds all numeric arguments passed to the script            |
| `4-hidden_discovery.py` | Lists names in a compiled `.pyc` file, skipping `__` names |
| `5-variable_load.py`  | Imports and prints the value of a variable from another file |

## Usage

Make scripts executable:

```bash
chmod +x *.py
