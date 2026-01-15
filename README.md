# libft

*This project has been created as part of the 42 curriculum by nandrian.*

## About

Libft is a custom C library that reimplements essential functions from the standard C library. This project serves as a foundation for future 42 projects, providing a reliable set of utility functions for string manipulation, memory management, character validation, and output operations.

## Building

To compile the library:

```bash
make
```

This generates `libft.a`, a static library that can be linked to your C programs.

## Usage

Include the header in your C files:

```c
#include "src/libft.h"
```

Compile your program with the library:

```bash
cc your_program.c libft.a -o your_program
```

## Functions

The library includes:

- **Character checks**: `ft_isalpha`, `ft_isdigit`, `ft_isalnum`, `ft_isascii`, `ft_isprint`
- **String operations**: `ft_strlen`, `ft_strchr`, `ft_strrchr`, `ft_strncmp`, `ft_strlcpy`, `ft_strlcat`, `ft_strdup`, `ft_substr`, `ft_strjoin`, `ft_strtrim`, `ft_split`, `ft_strnstr`
- **Memory functions**: `ft_memset`, `ft_bzero`, `ft_memcpy`, `ft_memmove`, `ft_memchr`, `ft_memcmp`, `ft_calloc`
- **Conversion**: `ft_atoi`, `ft_itoa`, `ft_toupper`, `ft_tolower`
- **String mapping**: `ft_strmapi`, `ft_striteri`
- **File descriptor output**: `ft_putchar_fd`, `ft_putstr_fd`, `ft_putendl_fd`, `ft_putnbr_fd`

## Cleaning

```bash
make clean   # Remove object files
make fclean  # Remove object files and library
make re      # Rebuild from scratch
```
