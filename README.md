Welcome to the Libft Project! This project is designed to help you understand and implement essential functions from the standard C library. By creating your own library, libft, you will gain a deeper understanding of how these functions work, which will be invaluable for your future C programming projects.
Project Name

libft.a

Objective

The objective of this project is to create a comprehensive library of functions that replicate standard C library functions and extend functionality with additional useful routines. This library will serve as a foundation for your subsequent C programming projects, ensuring you have a reliable set of tools at your disposal.
Description

The libft project requires you to implement a variety of functions, split into two main parts:
Part 1: Libc Functions

You will re-implement a set of functions from the standard C library (libc). These functions must have the same prototypes and behaviors as the originals, but with the prefix ft_. This exercise will help you understand the inner workings of standard C functions.
Part 2: Additional Functions

In addition to the libc functions, you will develop a set of additional functions that are not part of the standard C library or are implemented differently. These functions will enhance the functionality of your libft and provide more tools for your programming tasks.
Mandatory Part Details
Program Requirements

    Library Name: libft.a
    Turn-in Files: Makefile, libft.h, ft_*.c
    Makefile Rules: NAME, all, clean, fclean, re
    External Functions: None authorized
    Libft Authorized: Not applicable

Technical Considerations

    Global Variables: Declaring global variables is forbidden.
    Helper Functions: Define helper functions as static functions to limit their scope to the appropriate file.
    File Placement: Place all files at the root of your repository.
    Unused Files: Turning in unused files is forbidden.
    Compilation Flags: Every .c file must compile with the flags -Wall -Wextra -Werror.
    Library Creation: Use the ar command to create your library. The libtool command is forbidden.
    Library Location: Your libft.a must be created at the root of your repository.

Part 1 - Libc Functions

Re-implement the following standard C library functions with the ft_ prefix:

    Character Checks: isalpha, isdigit, isalnum, isascii, isprint
    String and Memory Operations: strlen, memset, bzero, memcpy, memmove, strlcpy, strlcat, toupper, tolower, strchr, strrchr, strncmp, memchr, memcmp, strnstr, atoi
    Memory Allocation: calloc, strdup

Part 2 - Additional Functions

Develop the following additional functions:

    Substring Creation: ft_substr - Creates a substring from a given string.
    String Joining: ft_strjoin - Concatenates two strings into a new string.
    String Trimming: ft_strtrim - Trims specified characters from the beginning and end of a string.
    String Splitting: ft_split - Splits a string into an array of strings using a specified delimiter.
    Integer to String: ft_itoa - Converts an integer to a string.
    String Mapping: ft_strmapi - Applies a function to each character of a string, creating a new string.
    String Iteration: ft_striteri - Applies a function to each character of a string, modifying it in place.
    File Descriptor Operations:
        ft_putchar_fd - Outputs a character to a given file descriptor.
        ft_putstr_fd - Outputs a string to a given file descriptor.
        ft_putendl_fd - Outputs a string followed by a newline to a given file descriptor.
        ft_putnbr_fd - Outputs an integer to a given file descriptor.

Conclusion

The libft project is a foundational exercise that will significantly enhance your understanding of C programming. By implementing and using your own library, you will develop a deeper appreciation for the standard library functions and improve your coding skills. Happy coding!
