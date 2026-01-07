Mini OOP Shell

A simple command-line shell built in Python using object-oriented programming (OOP) concepts. This project was created as part of a systems programming learning journey, implementing basic shell features, including command execution, redirection, and autocompletion.

Features

Command Execution

Supports running both built-in commands (like cd, exit) and external programs in PATH.

Output Redirection

Handles > and 2> to redirect stdout and stderr to files.

Autocompletion

Partial and full command autocompletion using Python’s readline module.

OOP Design

Shell logic is encapsulated in classes:

Shell – manages state like current working directory and environment variables.

Command – represents commands and their execution.

Parser – parses input and handles redirection logic.

Error Handling

Gracefully handles invalid commands and invalid paths.

Project Structure
mini-oop-shell/
├─ your_program.py       # Main shell program
├─ parser.py             # Input parser and redirection handling
├─ command.py            # Command execution logic
├─ shell.py              # Shell class managing state and the loop
├─ README.md             # This file
└─ requirements.txt      # Optional, if any dependencies


How to Run

Clone the repository:

Run the shell:

python your_program.py


Try commands:

$ echo Hello World
$ ls
$ cd ..
$ pwd
$ ls > output.txt


Use <TAB> for autocompletion:

$ xyz_ <TAB>

What You Will Learn

By exploring this project, you will understand:

How shells manage state like current directory and environment variables.

How input parsing and tokenization works.

How to handle file descriptors and output redirection in Python.

Basics of OOP design applied to systems-level programs.

How to implement autocompletion with readline.

Future Improvements

Command history using readline or a custom implementation.

Background jobs (&) and job control.

Piping commands (|).

Support for more built-in commands.

Notes

This shell is intended for educational purposes.
It is not a full-featured shell, but a learning tool to understand systems programming concepts.
*Depending on your OS and computer specs, certain errors may occur

Author

Jesunifemi Oluwasanmi
Learning Systems Programming & OOP in Python $ Go
