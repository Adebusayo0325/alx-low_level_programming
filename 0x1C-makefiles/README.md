0x1B. C - Makefiles
What you should learn from this project

At the end of this project you are expected to be able to explain to anyone,  without the help of Google:
What are make, Makefiles
When, why and how to use Makefiles
What are a rules and how to set and use them
What are explicit and implicit rules
What are the most common / useful rules
What are variables and how to set and use them
Exercises

0. make -f 0-Makefile

Create your first Makefile.
Requirements:

name of the executable: holberton
rules: all
The all rule builds your executable
variables: none
1. make -f 1-Makefile

Requirements:

name of the executable: holberton
rules: all
The all rule build your executable
variables: CC, SRC
CC: the compiler to be used
SRC: the .c files
2. make -f 2-Makefile

Create your first useful Makefile.
Requirements:

name of the executable: holberton
rules: all
The all rule builds your executable
variables: CC, SRC, OBJ, NAME
CC: the compiler to be used
SRC: the .c files
OBJ: the .o files
NAME: the name of the executable
The all rule should recompile only the updated source files
You are not allowed to have a list of all the .o files
3. make -f 3-Makefile

Requirements:

name of the executable: holberton
rules: all, clean, oclean, fclean, re
all: builds your executable
clean: deletes all Emacs and Vim temporary files along with the executable
oclean: deletes the object files
fclean: deletes the Emacs temporary files, the executable, and the object files
re: forces recompilation of all source files
variables: CC, SRC, OBJ, NAME, RM
CC: the compiler to be used
SRC: the .c files
OBJ: the .o files
NAME: the name of the executable
RM: the program to delete files
The all rule
