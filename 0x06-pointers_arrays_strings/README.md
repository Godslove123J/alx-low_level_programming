
Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

General
What are pointers and how to use them
What are arrays and how to use them
What are the differences between pointers and arrays
How to use strings and how to manipulate them
Scope of variables
Copyright - Plagiarism
You are tasked to come up with solutions for the tasks below yourself to meet with the above learning objectives.
You will not be able to meet the objectives of this or any following project by copying and pasting someone else’s work.
You are not allowed to publish any content of this project.
Any form of plagiarism is strictly forbidden and will result in removal from the program.
Requirements
General
Allowed editors: vi, vim, emacs
All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89
All your files should end with a new line
A README.md file, at the root of the folder of the project is mandatory
Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl
You are not allowed to use global variables
No more than 5 functions per file
You are not allowed to use the standard library. Any use of functions like printf, puts, etc… is forbidden
You are allowed to use _putchar
You don’t have to push _putchar.c, we will use our file. If you do it won’t be taken into account
In the following examples, the main.c files are shown as examples. You can use them to test your functions, but you don’t have to push them to your repo (if you do we won’t take them into account). We will use our own main.c files at compilation. Our main.c files might be different from the one shown in the examples
The prototypes of all your functions and the prototype of the function _putchar should be included in your header file called main.h
Don’t forget to push your header file
Quiz questions
Question #0
What happens when one tries to dereference a pointer to NULL?


Segmentation fault


World War Z


Nothing


Kernel panic

Question #1
What is wrong with the following code?

int n = 5;
int array[5];
int i = 3;

array[n] = i;

It is impossible to declare the variable array this way


It is not possible to access array[n]


Nothing is wrong


The array array is not entirely initialized

Question #2
What is wrong with the following code?

int n = 5;
int array[n];
int i = 3;

array[n] = i;

It is impossible to declare the variable array this way


It is not possible to access array[n]


Nothing is wrong


The array array is not entirely initialized

Question #3
var = "Best";
What is the type of var?


string


char *


int *

Question #4
Why is it important to reserve enough space for an extra character when declaring/allocating a string?


For memory alignment


For fun


In case we need one


For the null byte (end of string)

Question #5
What is wrong with the following code?

int n = 5;
int array[10];
int i = 3;

array[n] = i;

It is impossible to declare the variable array this way


It is not possible to access array[n]


Nothing is wrong


The array array is not entirely initialized

Question #6
What is/are the difference(s) between the two following variables? (Except their names)

char *s1 = "";
char *s2 = NULL;

The first one can be dereferenced, not the second one


The first one points to a 0-byte, the second one points to 0


The second one can be dereferenced, not the first one


The first one points to 0, the second one points to a 0-byte


They are the same

Please make sure to validate all quiz questions before moving on to project tasks

