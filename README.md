# simple_shell
0x16. C - Simple Shell - group project at Alx - shellscripting - c_programming

**simple shell:_** project is building a simple command line prompt that takes the most basics of commands that are present in the bash shell and runs them. the program must have the exact same output as sh (/bin/sh) as well as the exact same error output.

The shell will work after being compiled using ** gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o hsh**

## Files in the directory

## Files
* `README.md` : contains information about this project
* `main.h` : Header file, contains all prototypes for funcitons used, as well as libriaries
* `hsh.c`: Main file that uses most functions and executes them within this file
* `_getenv.c` : gets an environment variable
* `_getline.c`: puts input from user into buffer line
* `which.c`: searches directories in PATH variable for command
* `builtin_execute.c`: Executing the builtins
* `builtins.c`: code contains 'for print'
* `child.c`: File that forks and creates parent child processes
* `free.c`: File with free malloc functions
* `prompt.c`: File checks mode and prints prompt if in interactive mode
* `tokenizer.c`: File that creates function to tokenize an array of strings
* `utility_functions.c`: helper functions
* `hsh.c`: contains the main loop f shell
## Launching the shell
After compiling the code run this `./shell`

* Output: prompt to terminal: `$ `

## Authors
* Helen Teka - https://github.com/93Helu
* Habtamu Wolde - https://github.com/Habtwolde
