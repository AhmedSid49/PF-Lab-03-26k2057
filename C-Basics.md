C Programming Basics

1. Data Types

Data Type Description
`int`  Stores whole numbers. 
`float` Stores single-precision decimal numbers. 
`double` Stores double-precision decimal numbers. 
`char` Stores a single character. 
`bool` Stores true or false values. 
`void` Represents the absence of a value. 

2. Format Specifiers

Format Specifier Purpose 
`%d` Signed decimal integer 
`%u` Unsigned decimal integer 
`%o` Octal integer 
`%x` Hexadecimal integer in lowercase 
`%X` Hexadecimal integer in uppercase 
`%f` Floating-point value 
`%e` Scientific notation 
`%c` Character 
`%s` String 
`%ld` Long integer 

3. Input/Output Functions

scanf() – Takes formatted input.
printf() – Displays formatted output.
getchar() – Reads one character.
putchar() – Displays one character.
fgets() – Reads a string, including spaces.
puts() – Displays a string followed by a new line.

4. Escape Sequences
\n	New line
\t	Tab
\\	Backslash
\"	Double quote
\'	Single quote

Example:
printf("Name:\tAli\nAge: 20");

5. Precision
Precision controls the number of digits displayed after the decimal point.

printf("%.2f", value);  // 2 digits
printf("%.4f", value);  // 4 digits
printf("%.6f", value);  // 6 digits

For example, 12.345678 can be displayed as:
12.35
12.3456
