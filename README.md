Shell is a program that provides a command-line interface for interacting with an operating system. It allows you to type commands that the computer will execute, and provides a way to navigate the file system, launch applications, and perform various other tasks.
<br />
#Syntax
<br />
The syntax for shell commands varies depending on the specific command and the shell being used. However, most shell commands follow a basic structure that includes the name of the command followed by one or more arguments.  
<br />
Built-ins
<br />
There are two built-ins programmed into the shell. 
<br />
- env - The env command is a command that tells the shell program to display all of the environment variables with their values. It is a way to access those values through the shell.
- exit - Terminates the current process and returns control to the operating system.
<br />
Files
<br />
- README.md: A list of current files and a brief explanation about this project.
<br />
- header.h: This is a header file, which uses functions, variables, and other constructs that are defined in source files and libraries.
<br />
- hsh.c: Runs the shell process. It’s the main file that uses and executes most functions within the file.
<br />
- _getenv.c: Functions which are used to retrieve and copy environment variables. 
<br />
- _getline.c: Puts input from user into the buffer line. 
<br />
- _which.c: Searches directories in path for commands. 
<br />
- built_exe.c: Executes the builtin functions. 
<br />
- builtins.c: Exits the shell. 
<br />
- freeing.c: Frees all possible malloc leaks at the end. 
<br />
- _child.c: Function for child process.
<br />
- _prompt.c: Checks mode and prints prompt. 
<br />
- _tokenization.c: Tokenizes a string. 
<br />
- errors.c: Prints errors based on case. 
<br />
- str_functions.c: Compares two strings, copies the string to buffer, then returns the length of a string. 
