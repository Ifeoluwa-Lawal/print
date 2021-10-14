## printf()
The printf project is a collaboration between LAWAL Ifeoluwa Adeola and Jolly Abu Daniel, actual students of Software Engineering at Alx School, the "_printf". It works like the actual printf command found in the standard Input/Output library. You can check through the manual 3 of printf and compare with this manual to see that they contain some basic features.

## Prototype for _printf()

	int _printf(const char *format, ...)

------------

## Examples
**String**
* Input: ```_printf("%s\n", 'Hello World.');```
* Output: ```Hello World.```

**Character**
* Input: ```_printf("The first letter in the alphabet is %c\n", 'A');```
* Output: ```The first letter in the alphabet is A```

**Integer**
* Input: ```_printf("This is a integer: %i\n", 12);```
* Output: ```This is a integer: 12```

------------

## Mandatory Tasks
- [x] Write function that produces output with conversion specifiers ```c```, ```s```, and ```%```.
- [x] Handle conversion specifiers ```d```, ```i```.
- [x] Create a man page for your function.
## Advanced Tasks
- [x] Handle conversion specifier ```b```.
- [x] Handle conversion specifiers ```u```, ```o```, ```x```, ```X```.
- [ ] Use a local buffer of 1024 chars in order to call write as little as possible.
- [x] Handle conversion specifier ```S```.
- [x] Handle conversion specifier ```p```.
- [ ] Handle flag characters ```+```, space, and ```#``` for non-custom conversion specifiers.
- [ ] Handle length modifiers ```l``` and ```h``` for non-custom conversion specifiers.
- [ ] Handle the field width for non-custom conversion specifiers.
- [ ] Handle the precision for non-custom conversion specifiers.
- [ ] Handle the ```0``` flag character for non-custom conversion specifiers.
- [x] Handle the custom conversion specifier ```r``` that prints the reversed string.
- [x] Handle the custom conversion specifier ```R``` that prints the rot13'ed string.
- [ ] All above options should work well together.

------------

## File Functions
Files | Description
--- | ---
`_printf.c` | Own Printf Function Tha Performs Formatted Output Conversion And Print Data
`main.h` | Header File Were All Prototypes Are Saved
`get_print_func.c` | Pointer To A Function That Selects The Correct Function To Perform The Operation
`print_buf.c` | Function That Prints The Buffer
`handl_buf.c` | Function That Concatenates The Buffer Characters
`print_chr.c` | Function That Writes The Character C To Stdio
`print_str.c` | Function That Writes The String To Stdout
`print_int.c` | Function That Prints An Integer
`print_bnr.c` | Function That Prints Decimal In Binary
`print_oct.c` | Function That Prints Decimal In Octal
`print_hex.c` | Function That Prints Decimal In Hexadecimal
`print_upx.c` | Function That Prints Decimal In Uppercase Hexadecimal
`print_usr.c` | Function That Prints A String And Values Of Non-Printed Chars
`print_unt.c` | Function That Prints An Unsigned Integer
`print_rev.c` | Function That Writes The String To Stdout In Reverse
`print_rot.c` | Function That Writes The String To Stdout In Rot13
`print_add.c` | Function That Prints The Address Of An Input Variable
`print_long_oct.c` | Function That Prints Long Decimal Number In Octal
`print_long_hex.c` | Function That Prints Long Decimal Number In Hexadecimal
`print_long_int.c` | Function That Prints  A Long Integer
`print_long_upx.c` | Function That Prints A Long Decimal In Uppercase Hexadecimal
`print_long_unt.c` | Function That Prints A Long Unsigned Integer
`print_short_oct.c` | Function That Prints Short Decimal Number In Octal
`print_short_hex.c` | Function That Prints Short Decimal Number In Hexadecimal
`print_short_int.c` | Function That Prints  A Short Integer
`print_short_upx.c` | Function That Prints A Short Decimal In Uppercase Hexadecimal
`print_short_unt.c` | Function That Prints A Short Unsigned Integer
`print_num_hex.c` | Function That Print A Number In Hexadecimal Begining With 0 And x
`print_num_oct.c` | Function That Prints A Number In Octal Begining With 0 And o
`print_num_upx.c` | Function That Prints A Number In Uppercase Hexadecimal
`print_plus_int.c` | Function That Prints An Integer With Plus Symbol
`print_space_int.c` | Function That Prints An Integer Begining With 0 And u
`ev_print_func.c` | Function That Returns The Amount Of Indetifiers
---

### Authors
[LAWAL Ifeoluwa Adeola](https://github.com/Ifeoluwa-Lawal)

[JOLLY Abu Daniel](https://github.com/Jollyabu)
