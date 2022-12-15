# simple_shell
0x16. C - Simple Shell - group project at Alx - shellscripting - c_programming

**simple shell:_** project is building a simple command line prompt that takes the most basics of commands that are present in the bash shell and runs them. the program must have the exact same output as sh (/bin/sh) as well as the exact same error output.

The shell will work after being compiled using ** gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o hsh**

#### HOME
The home directory of the current user and the default directory argument for the **cd** builtin command.

#### PWD
The current working directory as set by the **cd** command.


#### OLDPWD
The previous working directory as set by the **cd** command.

#### PATH
A colon-separated list of directories in which the shell looks for commands. A null directory name in the path (represented by any of two adjacent colons, an initial colon, or a trailing colon) indicates the current directory.

#### $ENV_VARIABLE
`ENV_VARIABLE` is substituted with its value.

#### $?
`?` is substitued with the return value of the last program executed.

#### $$
The second `$` is substitued with the current process ID.

#### ; - Command separator
Commands separated by a `;` are executed sequentially.

#### && - AND logical operator
`command1 && command2`: `command2` is executed if, and only if, `command1` returns an exit status of zero.

#### || - OR logical operator
`command1 || command2`: `command2` is executed if, and only if, `command1` returns a non-zero exit status.

The operators `&&` and `||` have equal precedence, followed by `;`.


### Builtin Commands

#### cd
  * Usage: `cd [DIRECTORY]`
  * Changes the current directory of the process to `DIRECTORY`.
  * If no argument is given, the command is interpreted as `cd $HOME`.
  * If the argument `-` is given, the command is interpreted as `cd $OLDPWD` and the pathname of the new working directory is printed to standad output.
  * If the argument, `--` is given, the command is interpreted as `cd $OLDPWD` but the pathname of the new working directory is not printed.
  * The environment variables `PWD` and `OLDPWD` are updated after a change of directory.



#### exit
  * Usage: `exit [STATUS]`
  * Exits the shell.
  * The `STATUS` argument is the integer used to exit the shell.
  * If no argument is given, the command is interpreted as `exit 0`.

#### env
  * Usage: `env`
  * Prints the current environment.

#### setenv
  * Usage: `setenv [VARIABLE] [VALUE]`
  * Initializes a new environment variable, or modifies an existing one.
  * Upon failure, prints a message to `stderr`.

#### unsetenv
  * Usage: `unsetenv [VARIABLE]`
  * Removes an environmental variable.
  * Upon failure, prints a message to `stderr`.

## Launching the shell
After compiling the code run this `./shell`

* Output: prompt to terminal: `$ `

## Authors
* Helen Teka - https://github.com/93Helu
* Habtamu Wolde - https://github.com/Habtwolde
