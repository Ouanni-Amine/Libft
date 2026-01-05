<p align="center">
  <img src="https://raw.githubusercontent.com/Ouanni-Amine/Assets/main/LIBFT/LIBFT.png" alt="libft logo" width="220">
</p>

<h1 align="center">Libft</h1>
<p align="center">A small C library of essential and custom utility functions</p>

📋 **Table of Contents**

- [📄 Description](#-description)
- [🛠️ Technologies Used](#%EF%B8%8F-technologies-used)
- [🔑 Key Concepts](#-key-concepts)
- [📁 Project Structure](#-project-structure)
- [📌 Mandatory Functions](#-mandatory-functions)
- [✨ Bonus Functions](#-bonus-functions)
- [⚙️ How to Compile](#%EF%B8%8F-how-to-compile)
- [🛠 How to Use](#-how-to-use)

## 📄 Description

Libft is a custom C library containing reimplemented standard functions
from `<ctype.h>`, `<string.h>`, `<stdlib.h>`, plus additional utilities
and linked-list tools. It is the first project in the 42 curriculum
and teaches the fundamentals of memory management, string handling,
and data manipulation in C.

## 🛠️ Technologies used

<p align="center">
  <img src="https://img.icons8.com/color/480/c-programming.png" width="60"/>
  &nbsp;&nbsp;&nbsp;
  <img src="https://img.icons8.com/color/480/git.png" width="60"/>
  &nbsp;&nbsp;&nbsp;
  <img src="https://www.gnu.org/graphics/heckert_gnu.small.png" width="60"/>
  &nbsp;&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/refs/heads/main/icons/vim.png" width="60"/>
</p>

## 🔑 Key concepts

<b>1.Memory Manipulation</b><br>
<b>2.Memory Management</b><br>
<b>3.Pointer arithmetic</b><br>
<b>4.String Manipulation</b><br>
<b>5.Function Pointers</b><br>
<b>6.File Descriptors</b><br>
<b>8.Linked Lists DSA</b><br>
<b>9.Error Handling</b><br>

## 📁 Project structure
```
├── Makefile
├── ft_atoi.c
├── ft_bzero.c
├── ft_calloc.c
├── ft_isalnum.c
├── ft_isalpha.c
├── ft_isascii.c
├── ft_isdigit.c
├── ft_isprint.c
├── ft_itoa.c
├── ft_lstadd_back_bonus.c
├── ft_lstadd_front_bonus.c
├── ft_lstclear_bonus.c
├── ft_lstdelone_bonus.c
├── ft_lstiter_bonus.c
├── ft_lstlast_bonus.c
├── ft_lstmap_bonus.c
├── ft_lstnew_bonus.c
├── ft_lstsize_bonus.c
├── ft_memchr.c
├── ft_memcmp.c
├── ft_memcpy.c
├── ft_memmove.c
├── ft_memset.c
├── ft_putchar_fd.c
├── ft_putendl_fd.c
├── ft_putnbr_fd.c
├── ft_putstr_fd.c
├── ft_split.c
├── ft_strchr.c
├── ft_strdup.c
├── ft_striteri.c
├── ft_strjoin.c
├── ft_strlcat.c
├── ft_strlcpy.c
├── ft_strlen.c
├── ft_strmapi.c
├── ft_strncmp.c
├── ft_strnstr.c
├── ft_strrchr.c
├── ft_strtrim.c
├── ft_substr.c
├── ft_tolower.c
├── ft_toupper.c
└── libft.h
```

## 📌 Mandatory Functions

| **Family**    | **Function**       | **Description**                                         |
|---------------|------------------|---------------------------------------------------------|
| Character     | ft_isalpha       | Checks if character is alphabetic                      |
| Character     | ft_isdigit       | Checks if character is a digit                          |
| Character     | ft_isalnum       | Checks if character is alphanumeric                     |
| Character     | ft_isascii       | Checks if character is ASCII                            |
| Character     | ft_isprint       | Checks if character is printable                        |
| Character     | ft_toupper       | Converts character to uppercase                         |
| Character     | ft_tolower       | Converts character to lowercase                         |
| Memory        | ft_bzero         | Sets `n` bytes of memory to zero                        |
| Memory        | ft_calloc        | Allocates memory and initializes it to zero            |
| Memory        | ft_memchr        | Locates a byte in memory                                |
| Memory        | ft_memcmp        | Compares two memory areas                               |
| Memory        | ft_memcpy        | Copies `n` bytes from source to destination            |
| Memory        | ft_memmove       | Copies memory safely even if areas overlap             |
| Memory        | ft_memset        | Fills memory with a constant byte                       |
| String        | ft_strlen        | Returns the length of a string                          |
| String        | ft_strlcpy       | Copies a string into a buffer of given size            |
| String        | ft_strlcat       | Concatenates strings into a buffer of given size       |
| String        | ft_strchr        | Returns a pointer to the first occurrence of char      |
| String        | ft_strrchr       | Returns a pointer to the last occurrence of char       |
| String        | ft_strncmp       | Compares two strings up to `n` characters              |
| String        | ft_strnstr       | Locates a substring in a string up to `len` characters |
| String        | ft_strdup        | Duplicates a string                                     |
| String        | ft_substr        | Returns a substring from a string                       |
| String        | ft_strjoin       | Concatenates two strings into a new string             |
| String        | ft_strtrim       | Trims characters from the start and end of a string    |
| String        | ft_split         | Splits a string into an array of strings by delimiter  |
| String        | ft_strmapi       | Applies a function to each character of a string       |
| String        | ft_striteri      | Applies a function to each character with index        |
| Conversion    | ft_atoi          | Converts a string to an integer                         |
| Conversion    | ft_itoa          | Converts an integer to a string                         |
| File Desc     | ft_putchar_fd    | Writes a character to a file descriptor                |
| File Desc     | ft_putstr_fd     | Writes a string to a file descriptor                   |
| File Desc     | ft_putendl_fd    | Writes a string followed by newline to a descriptor    |
| File Desc     | ft_putnbr_fd     | Writes an integer to a file descriptor                 |

## ✨ Bonus Functions

| Family        | Function            | Description                                         |
|---------------|-------------------|-----------------------------------------------------|
| Linked List   | ft_lstnew_bonus    | Creates a new list element                          |
| Linked List   | ft_lstadd_front_bonus | Adds a new element at the beginning of the list  |
| Linked List   | ft_lstadd_back_bonus  | Adds a new element at the end of the list        |
| Linked List   | ft_lstsize_bonus   | Counts the number of elements in the list         |
| Linked List   | ft_lstlast_bonus   | Returns the last element of the list              |
| Linked List   | ft_lstdelone_bonus | Deletes one element using a function              |
| Linked List   | ft_lstclear_bonus  | Deletes and frees all elements of the list        |
| Linked List   | ft_lstiter_bonus   | Iterates through the list and applies a function  |
| Linked List   | ft_lstmap_bonus    | Applies a function to each element and creates a new list |

## ⚙️ How to Compile

• Compile the library
```
make

# This generates:
# - libft.a : the static library
# - Object files (.o) for each source file
```

• Remove object files
```
make clean
```

• Remove object files and the library
```
make fclean
```

• Rebuild everything
```
make re
```

## 🛠 How to Use

• Include the header
```
#include "libft.h"
```

• Compile your program with:
```
gcc -Wall -Wextra -Werror main.c -L. -lft -o my_program
```
