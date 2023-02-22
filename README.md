# ALX Software Engineering Printf Team Project

## Description

This team project is a custom made printf function for the C programming language called **_printf**. It has been optimized to take various inputs and optional arguments based exactly on how the standard library function printf works. We submitted this as part of the ALX software engineering course requirement for grading.

## Prototype
`int_printf(const char *format, ...);`

## Format of the format string
The format string is a character string starting and ending with double quotes. The format string is composed of zero or more directives; ordinary characters (not %), and conversion specifications, each of which results in fetching zero or more subsequent arguments.

Each conversion specification is introduced by the character % and ends with a conversion specifier.

## The tasks
-[X] **I'm not going anywhere. You can print that wherever you want to. I'm here and I'm a Spur for life**.Write a function that produces output according to a format.

- Prototype: `int _printf(const char *format, ...);`
- Returns: the number of characters printed (excluding the null byte used to end output to strings)
- write output to stdout, the standard output stream -format is a character string. The format string is composed of zero or more directives. See man 3 printf for more detail. You need to handle the following conversion specifiers: -- `c` -- `s` -- `%` | | -[x] **Education is when you read the fine print. Experience is what you get if you don't** Handle the following conversion specifiers: -- `d` -- `i`

## Functions we use
```
int _putchar(char c); /*writes the character c to stdout */
int _printf(const char *format, ...);/* function that produces output according to a format.*/
int print_char(va_list c);/*writes the character c to stdout */
int print_string(va_list s);/*writes the character c to stdout */
int print_int(va_list i);/*function that prints an integer */
int print_dec(va_list d);/* function that prints an decimal*/
```
## Contributors
* [Vivianne](https://github.com/Vivi-anne/printf)
* [Peter](https://github.com/virtuoso254)
