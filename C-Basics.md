# Basics in C

## Data Types
| Data Type | Description |
|:---------:|:-----------:|
|int| Whole numbers that can have both positive, negative, and zero values but no decimal values. It can take 232 distinct states.|
|float|Floating type variables can hold real numbers with a precision of 6 digits.|
|double|Floating type variables can hold real numbers with precision of 14 digits.|
|char|Character data type allows a variable to store only one character.|
|bool|A boolean data type that can hold one of two values: true (1) or false (0).|
|void|A special data type that signifies the absence of a value. It is most often used with functions that do not return a value or with generic pointers.|

## Format Specifiers
| Format Specifier | Description |
|:---:|:---:|
|%d/%i|It is used to print the signed integer value where signed integer means that the variable can hold both positive and negative values.|
|%u|It is used to print the unsigned integer value where the unsigned integer means that the variable can hold only positive value.|
|%o|It is used to print the octal unsigned integer where octal integer value always starts with a 0 value.|
|%x|It is used to print the hexadecimal unsigned integer where the hexadecimal integer value always starts with a 0x value. In this, alphabetical characters are printed in small letters such as a, b, c, etc.|
|%X|It is used to print the hexadecimal unsigned integer, but %X prints the alphabetical characters in uppercase such as A, B, C, etc.|
|%f|It is used for printing the decimal floating-point values. By default, it prints the 6 values after '.'.|
|%e/%E|It is used for scientific notation. It is also known as Mantissa or Exponent.|
|%g|It is used to print the decimal floating-point values, and it uses the fixed precision, i.e., the value after the decimal in input would be exactly the same as the value in the output.|
|%p|It is used to print the address in a hexadecimal form.|
|%c|It is used to print the unsigned character.|
|%s|It is used to print the strings.|
|%ld|It is used to print the long-signed integer value.|

## Input/Output Functions
| Function | Description |
|:---:|:---:|
|scanf()|The scanf() function is used to read and store formatted input from the standard input (stdin). Its syntax is scanf("format string", &variable);, where the format string specifies the type of data to be read.|
|printf()|The printf() function is used to write formatted output to the standard output (stdout). Its syntax is  printf("format string", arguments);, where the format string can contain literal text, format specifiers, and escape sequences.|
|getchar()|Reads and returns a single character from the input. Its syntax is getchar();.|
|putchar()|Writes a single character to the output. Its syntax is putchar();.|
|fgets()|Reads a line of text (including spaces) from stdin into a character array. Its syntax is fgets(var_name, length, stdin);, where var_name is an array of characters and length specifies the maximum length of the string.|
|puts()|Writes a string to stdout, automatically adding a newline character at the end. Its syntax is puts(var_name);.|

## Escape Sequences
| Symbol | Function |
|:---:|:---:|
|\t|Inserts a tab in the text.|
|\b|Inserts a backspace in the text.|
|\n|Inserts a newline in the text.|
|\r|Inserts a carriage return in the text.|
|\f|Inserts a form feed in the text.|
|\'|Inserts a single quote character in the text.|
|\"|Inserts a double quote character in the text.|
|\\|Inserts a backslash character in the text.|
|\?|Inserts a question mark in the text.|
|\a|Play beep or Alarm|

## Precision
Precision is specified by the number of digits after the decimal point for the outputs for float as well as double numbers.\
If precision is not specified, it would be according to the default setting in the computer which is generally 6 digits.\
The precision may be specified in the format specifiers place by a period(.) followed by a positive number equal to the number of digits desired.\
For Example: %.2f, %.14lf
