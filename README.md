<!DOCTYPE html>

<html>



<img src="https://s3.amazonaws.com/intranet-projects-files/holbertonschool-low_level_programming/235/shell.jpeg" alt="">

    <h3>

        Description

    </h3>

    <hr>

    <p>This team project is part of the first year curriculum of Holberton School. Simple Shell is a command line interpreter that replicates the sh program on Linux. It can take in simple commands to navigate the terminal, manipulate files, and execute programs.

    </p>

    <p>What we learned:</p>

    <ul>

        <li>How a shell works and finds commands</li>

        <li>Creating, forking and working with processes</li>

        <li>Executing a program from another program</li>

        <li>Handling dynamic memory allocation in a large program</li>

        <li>Pair programming and team work</li>

        <li>Building a test suite to check our own code</li>

    </ul>

    <hr>

    <h3>Compile and run</h3>

    <p>gcc -Wall -Werror -Wextra -pedantic *.c -o hsh

    </p>

    <p>./hsh</p>

    <h3>Usage</h3>

    <hr>

    <ul>

        <li>

            Prints a prompt and waits for a command from the user

        </li>

        <li>

            Creates a child process in which the command is checked

        </li>

        <li>

            Checks for built-ins, aliases in the PATH, and local executable programs

        </li>

        <li>

            The child process is replaced by the command, which accepts arguments

        </li>

        <li>

            When the command is done, the program returns to the parent process and prints the prompt

        </li>

        <li>

            The program is ready to receive a new command

        </li>

        <li>

            To exit: press Ctrl-D or enter "exit" (with or without a status)

        </li>

        <li>

            Works also in non interactive mode

        </li>



    </ul>




</html>
