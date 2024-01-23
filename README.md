# LIBFT

This repository contains my implementation of the Libft project, which is the first project at 1337.

The goal of Libft is to recreate a set of functions from the standard C library, thereby enhancing understanding of fundamental programming concepts.

Contents
Main Library Functions

- `ft_memmove.c`: Move memory block.
- `ft_atoi.c`: Convert string to integer.
- `ft_memset.c`: Fill memory with a constant byte.
- `ft_bzero.c`: Set a block of memory to zero.
- `ft_putchar_fd.c`: Write character to a file descriptor.
- `ft_calloc.c`: Allocate and zero-initialize memory.
- `ft_isalnum.c`: Check if a character is alphanumeric.
- `ft_putendl_fd.c`: Write a string followed by a newline to a file descriptor.
- `ft_isalpha.c`: Check if a character is alphabetic.
- `ft_putstr_fd.c`: Write a string to a file descriptor.
- `ft_isascii.c`: Check if a character is an ASCII character.
- `ft_split.c`: Split a string into an array of substrings.
- `ft_isdigit.c`: Check if a character is a digit.
- `ft_strchr.c`: Locate the first occurrence of a character in a string.
- `ft_isprint.c`: Check if a character is printable.
- `ft_strdup.c`: Duplicate a string.
- `ft_itoa.c`: Convert an integer to a string.
- `ft_striteri.c`: Apply a function to each character of a string.
- `ft_strjoin.c`: Concatenate two strings.
- `ft_strlcat.c`: Concatenate strings with length control.
- `ft_strlcpy.c`: Copy strings with length control.
- `ft_strlen.c`: Calculate the length of a string.
- `ft_strmapi.c`: Apply a function to each character of a string with index.
- `ft_strncmp.c`: Compare two strings up to a specified number of characters.
- `ft_strnstr.c`: Locate a substring within a string with length control.
- `ft_strrchr.c`: Locate the last occurrence of a character in a string.
- `ft_strtrim.c`: Trim leading and trailing whitespaces from a string.
- `ft_substr.c`: Extract a substring from a string.
- `ft_memchr.c`: Locate a byte in a memory block.
- `ft_tolower.c`: Convert a character to lowercase.
- `ft_memcmp.c`: Compare two memory blocks.
- `ft_toupper.c`: Convert a character to uppercase.
- `ft_memcpy.c`: Copy memory area.

Bonus Functions
- `ft_lstnew.c`: Create a new linked list element.
- `ft_lstadd_front.c`: Add an element to the front of a linked list.
- `ft_lstadd_back.c`: Add an element to the back of a linked list.
- `ft_lstclear.c`: Clear the entire linked list.
- `ft_lstiter.c`: Iterate over a linked list and apply a function to each element.
- `ft_lstlast.c`: Get the last element of a linked list.
- `ft_lstmap.c`: Create a new list resulting from the application of a function to each element.
- `ft_lstsize.c`: Count the number of elements in a linked list.
  
Build and Usage
Compilation
To compile the libft library, simply run make in your terminal. This will generate the libft.a archive.

Usage in Projects
Include the libft.h header in your C projects, and make sure to link with the libft library during compilation. For example:

#include "libft.h"

int main() {
    ft_putstr_fd("Hello, libft!\n", 1);
    return 0;
}

Cleaning Up
Removing Object Files
To remove the object files, run make clean.

Full Clean-Up
For a complete clean-up (removing object files and the library), run make fclean.

Rebuilding
To rebuild the entire project, run make re.

Feel free to explore the source files for detailed documentation on each function's behavior and usage. Contributions and feedback are always welcome as I continue to refine and expand this library. Happy coding!

