# C-Projects

## Author: Debatra das

## 1. **<stdio.h> (Standard Input/Output Library)**

This library provides functions for handling input and output operations.

### Common functions:

- **printf()** – Prints formatted output to stdout.
- **scanf()** – Reads formatted input from stdin.
- **putchar()** – Writes a single character to stdout.
- **getchar()** – Reads a single character from stdin.
- **puts()** – Writes a string followed by a newline to stdout.
- **gets()** (deprecated) – Reads a string from stdin (unsafe, use `fgets()` instead).
- **fgets()** – Reads a string from a file (or stdin).
- **fputc()** – Writes a single character to a file.
- **fgetc()** – Reads a single character from a file.
- **fputs()** – Writes a string to a file.
- **fprintf()** – Writes formatted output to a file.
- **fscanf()** – Reads formatted input from a file.
- **fopen()** – Opens a file in a specified mode.
- **fclose()** – Closes an open file.
- **fseek()** – Moves the file pointer to a specific position.
- **ftell()** – Returns the current position of the file pointer.
- **rewind()** – Moves the file pointer to the beginning of a file.
- **feof()** – Checks if the end of the file has been reached.
- **ferror()** – Checks for file errors.
- **clearerr()** – Clears the error and end-of-file indicators for a file.

---

## 2. **<stdlib.h> (Standard Library)**

This library contains functions for memory allocation, process control, conversions, and random number generation.

### Common functions:

- **malloc()** – Allocates a specified number of bytes in memory.
- **calloc()** – Allocates memory for an array and initializes it to zero.
- **realloc()** – Changes the size of allocated memory.
- **free()** – Deallocates previously allocated memory.
- **exit()** – Terminates the program.
- **abort()** – Abnormally terminates the program.
- **atexit()** – Registers a function to be executed on normal termination.
- **system()** – Executes a system command.
- **atoi()** – Converts a string to an integer.
- **atof()** – Converts a string to a floating-point number.
- **atol()** – Converts a string to a long integer.
- **strtod()** – Converts a string to a double.
- **strtol()** – Converts a string to a long integer.
- **rand()** – Generates a pseudo-random number.
- **srand()** – Seeds the random number generator.
- **bsearch()** – Performs a binary search.
- **qsort()** – Sorts an array using the quicksort algorithm.

---

## 3. **<string.h> (String Handling Library)**

Provides functions for manipulating C-style strings (null-terminated character arrays).

### Common functions:

- **strlen()** – Returns the length of a string.
- **strcpy()** – Copies a string into another.
- **strncpy()** – Copies up to a specified number of characters.
- **strcat()** – Appends a string to another.
- **strncat()** – Appends up to a specified number of characters.
- **strcmp()** – Compares two strings.
- **strncmp()** – Compares a specified number of characters in two strings.
- **strchr()** – Finds the first occurrence of a character in a string.
- **strrchr()** – Finds the last occurrence of a character in a string.
- **strstr()** – Finds the first occurrence of a substring in a string.
- **strtok()** – Tokenizes a string.
- **memcpy()** – Copies a block of memory.
- **memmove()** – Moves a block of memory safely.
- **memset()** – Sets a block of memory to a specific value.
- **memcmp()** – Compares two blocks of memory.

---

## 4. **<math.h> (Mathematical Library)**

Provides mathematical functions such as trigonometric, logarithmic, and power functions.

### Common functions:

- **pow()** – Computes the power of a number.
- **sqrt()** – Computes the square root.
- **exp()** – Computes the exponential function (e^x).
- **log()** – Computes the natural logarithm.
- **log10()** – Computes the base-10 logarithm.
- **sin()** – Computes the sine of an angle.
- **cos()** – Computes the cosine of an angle.
- **tan()** – Computes the tangent of an angle.
- **asin()** – Computes the inverse sine.
- **acos()** – Computes the inverse cosine.
- **atan()** – Computes the inverse tangent.
- **fabs()** – Computes the absolute value of a floating-point number.
- **ceil()** – Rounds a number up to the nearest integer.
- **floor()** – Rounds a number down to the nearest integer.
- **fmod()** – Computes the remainder of a floating-point division.

---

## 5. **<ctype.h> (Character Handling Library)**

Provides functions for testing and converting characters.

### Common functions:

- **isalpha()** – Checks if a character is a letter.
- **isdigit()** – Checks if a character is a digit.
- **isalnum()** – Checks if a character is alphanumeric.
- **isspace()** – Checks if a character is a whitespace.
- **isupper()** – Checks if a character is an uppercase letter.
- **islower()** – Checks if a character is a lowercase letter.
- **toupper()** – Converts a character to uppercase.
- **tolower()** – Converts a character to lowercase.

---

## 6. **<time.h> (Time and Date Library)**

Provides functions for handling time and date.

### Common functions:

- **time()** – Returns the current time in seconds since the epoch.
- **clock()** – Returns the processor time.
- **difftime()** – Computes the difference between two times.
- **mktime()** – Converts a `tm` structure to a time_t value.
- **asctime()** – Converts a `tm` structure to a string.
- **ctime()** – Converts a time_t value to a string.
- **gmtime()** – Converts a time_t value to a `tm` structure in UTC.
- **localtime()** – Converts a time_t value to a `tm` structure in local time.
- **strftime()** – Formats time and date.

---

## 7. **<limits.h> (Integer Limits Library)**

Defines constants for the limits of integer types.

### Examples:

- **INT_MAX** – Maximum value of an int.
- **INT_MIN** – Minimum value of an int.
- **LONG_MAX** – Maximum value of a long.
- **LONG_MIN** – Minimum value of a long.
- **CHAR_MAX** – Maximum value of a char.
- **CHAR_MIN** – Minimum value of a char.

---

## 8. **<float.h> (Floating-Point Limits Library)**

Defines constants for the limits of floating-point types.

### Examples:

- **FLT_MAX** – Maximum value of a float.
- **FLT_MIN** – Minimum value of a float.
- **DBL_MAX** – Maximum value of a double.
- **DBL_MIN** – Minimum value of a double.
- **LDBL_MAX** – Maximum value of a long double.

---

## 9. **<assert.h> (Assertion Library)**

Provides a macro for debugging.

### Common function:

- **assert()** – Aborts the program if the given expression evaluates to false.

---

## 10. **<errno.h> (Error Handling Library)**

Defines macros for error reporting.

### Examples:

- **errno** – Stores error codes.
- **EDOM** – Domain error in mathematical functions.
- **ERANGE** – Result out of range.
- **EILSEQ** – Illegal byte sequence error.

---
