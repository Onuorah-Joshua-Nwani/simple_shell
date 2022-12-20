## 0x16. C - Simple Shell

<img src="https://s3.amazonaws.com/intranet-projects-files/holbertonschool-low_level_programming/235/shell.jpeg" alt="">

## Description:

This team project is part of the first year curriculum of Holberton School. Simple Shell is a command line interpreter that replicates the sh program on Linux. It can take in simple commands to navigate the terminal, manipulate files, and execute programs.

What we learned:

* How a shell works and finds commands
* Creating, forking and working with processes
* Executing a program from another program
* Handling dynamic memory allocation in a large program
* Pair programming and team work
* Building a test suite to check our own code

## Compile and run
```gcc -Wall -Werror -Wextra -pedantic *.c -o hsh```

```./hsh```

## Usage

* Prints a prompt and waits for a command from the user
* Creates a child process in which the command is checked
* Checks for built-ins, aliases in the PATH, and local executable programs
* The child process is replaced by the command, which accepts arguments
* When the command is done, the program returns to the parent process and prints the prompt
* The program is ready to receive a new command
* To exit: press Ctrl-D or enter "exit" (with or without a status)
* Works also in non interactive mode
