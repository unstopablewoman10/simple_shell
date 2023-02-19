simple_shell project

This repository contains the files for ALX simple_shell. It can be compiled using GCC and will execute a simple shell that can be used for some basic tasks and programs most commonly found in the /bin/ folder.

GCC command to compile:
gcc -Wall -Werror -Wextra -pedantic *.c -o hsh

This wil compile all the '.c' files and change the output's name to 'hsh'.

Template to test output:
============= $ ./hsh

($)

hsh main.c shell.c

$ exit $

After you clone this repository and compile the program with the command above, you will generate a file called hsh that can be executed by entering ./hsh in your shell.

The output after the program is executed should look something like this:

$|
Where you will get a prompt in the shape of a dollar sign so you can start typing commands into your shell. A good example of how it should execute is the command shown above were the user enters 'ls' and then gets a list of the directory contents.

Function Prototypes:
Brief description of functions contained in project:

_strcmpdir : compares strings to find dir. find_command : finds command to execute in path routes. charput : writes the character like putchar. place : similar to puts in C. _strlen : string length. str_concat : concatenate strings. lookforslash : identify if first char is a '/'. compareExit : checks if user typed exit. compareEnv : checks if user typed env. execute_proc : receives command and args from getline to be executed. identify_string : returns pointer with folder address. prompt : infinite loop with fork to keep prompt going. controlC: avoid program closing when pressing ctrl + c. main: initialize program.
