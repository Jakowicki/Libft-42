# Libft Project 📚

## Project Overview 🌟

Welcome to the Libft Project! This project is a custom implementation of several essential functions from the C standard library, along with some additional utility functions. The goal is to re-create commonly used library functions from scratch, providing a deeper understanding of their inner workings and improving programming skills in C.

## Table of Contents 📑

- Introduction
- Features
- Setup and Installation
- Usage
- Implemented Functions
- Contributing
- License

## Introduction 📖

The Libft Project involves writing your own versions of a variety of standard C library functions, as well as some additional helper functions. This project is a fundamental part of many C programming curriculums and is an excellent way to solidify your understanding of low-level programming concepts.

## Features ✨

Custom implementations of many standard C library functions.
Additional utility functions for string manipulation, memory allocation, and linked list operations.
Modular and reusable code suitable for integration into other projects.
Comprehensive test cases to ensure correctness and reliability.

## Setup and Installation ⚙️

Clone the repository:
-
```sh
_git clone https://github.com/Jakowicki/Libft-42.git_
```
Navigate to the project directory:
-
cd libft

Compile the library:
-
make

Usage 🚀
-
To use the compiled library in your own projects, include the libft.h header file and link the compiled library:

Include the header in your source files:
-
#include "libft.h"

Compile your project with the libft library:
-

gcc -o your_program your_program.c -L. -lft

## Implemented Functions 🛠️

#### Part 1 - Libc Functions ✅


- memset

- bzero

- memcpy

- memccpy

- memmove

- memchr

- memcmp

- strlen

- strlcpy

- strlcat

- strchr

- strrchr

- strnstr

- strncmp

- atoi

- isalpha

- isdigit

- isalnum

- isascii

- isprint

- toupper

- tolower

#### Part 2 - Additional Functions ✅

- substr

- strjoin

- strtrim

- split

- itoa

- strmapi

- putchar_fd

- putstr_fd

- putendl_fd

- putnbr_fd

#### Part 3 - Bonus Functions (Linked List) ❌

- lstnew

- lstadd_front

- lstsize

- lstlast

- lstadd_back

- lstdelone

- lstclear

- lstiter

- lstmap

## Contributing 🤝

Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request. Make sure to follow the coding standards and include appropriate tests.

## License 📜
This project is licensed under the MIT License. See the LICENSE file for details.

Thank you for checking out the Libft Project! Happy coding! 🎉
