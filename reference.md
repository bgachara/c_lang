# C reference

`This is my personal C programming language reference`

- The primary purpose of a high-level language is to permit more direct expression of a programmer's design.
- Programming in a high-level is about communicating a software design to programmer's not to the computer, hence focus should be on modularity and readability rather than speed.

## General Notes about the language

- The language has only 32 keywords.
- Provides no operations to deal directly with composite objects such as lists and arrays.
- No memory management facilities apart from static definition and stack allocation of local variables.
- It comes with a standard library of functions that provide a collection of commonly used operations
- Heavy use of pointers via the * character.
- DEFINE keyword used to introduce symbolic constants.
- Function pointers are used to implement C class like features.

## First Program

```c
#include <stdio.h>

int main(void)
{
    printf("Hello World!!\n")
}
```