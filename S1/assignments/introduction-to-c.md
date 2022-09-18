# C Language Introduction

## What is C?

C is a procedural programming language initially developed by Dennis Ritchie in the year 1972.
It is a very popular language, despite being old. C is strongly associated with UNIX, as it was developed to write the UNIX operating system.
The main features of the C language include low-level memory access, a simple set of keywords, and a clean style, which make C suitable for system programmings like an OS or compiler development.
C language is considered as the mother language of all the modern programming language because most of the compilers, JVM, Kernals, etc. are written in C language, and most of the programming languages follow C syntax, for example, C++, Java, C#, etc.

---

## Structure of a C program

By structure it is meant that, any C program can be written in this strucure only.
Writing a C program in any other structure will hence lead to a Comilation Error.
The structure of a C program is as follows:

1. Header
2. main()
3. Variable declaration
4. Body
5. Return

---

### Header Files Inclusion

The first and the foremost component is the inclusion of the Header files in a C program.
A header file is a file with extension .h which contains C function declarations and macro definitions to be shared between several source files.
Some of C Header files are:
  * `stdio.h`   - Defines core input and output functions.
  * `stddef.h`  - Defines several useful types and macros.
  * `stdint.h`  - Defines exact width integer types.
  * `stdlib.h`  - Defines numeric conversion functions, pseudo-random network generator, memory allocation
  * `string.h`  - Defines string handling functions
  * `math.h`    - Defines common mathematical functions

### Main Method Declaration

The next part of a C program is to declare the main() function. The syntax to declare the main function is:
```c
int main(){
  // code here
}
```

