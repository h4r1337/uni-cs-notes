# C Language Introduction

## What is C?

C is a procedural programming language initially developed by Dennis Ritchie in the year 1972.
It is a very popular language, despite being old. C is strongly associated with UNIX, as it was developed to write the UNIX operating system.
The main features of the C language include low-level memory access, a simple set of keywords, and a clean style, which make C suitable for system programmings like an OS or compiler development.
C language is considered as the mother language of all the modern programming language because most of the compilers, JVM, Kernals, etc. are written in C language, and most of the programming languages follow C syntax, for example, C++, Java, C#, etc.

---

## Structure of a C program

By structure it is meant that, any C program can be written in this strucure only.
Writing a C program in any other structure will hence lead to a Compilation Error.
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

---

### Main Method Declaration

The next part of a C program is to declare the main() function. The syntax to declare the main function is:
```c
int main(){
  // code here
}
```

---

### Variable Declaration

The next part of any C program is the variable declaration. It refers to the variable that are to be used in the function.
Please note that in the C program, no variable can be used without being declared. Also in a C program, the variables are to be declared before any operation in the function.

```c
int main() {
  int a;
}
```

---

### Body

The body of a function in the C program, refers to the operations that are performed in the functions. It can be anything like manipulations, searching, sorting, printing, etc.

```c
int main(){
  int a;
  printf("%d", a);
}
```

---

### Return statement

The last part of any C program is the return statement. The return statement refers to the returning of the values from a function.
This return statement and return value depend upon the return type of the function. For example, if the return type is void, then there will be no return statement.
In any other case, there will be a return statement and the return value will be of the type of the specified return type.


```c
int main(){
  int a;
  printf("%d", a);
  return 0;
}
```
