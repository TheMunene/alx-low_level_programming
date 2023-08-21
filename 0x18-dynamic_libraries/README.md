.a

files in Linux and

.lib

files in Windows.

Steps to create a static library

Let us create and use a Static Library in UNIX or UNIX like OS.

1.

Create a C file that contains functions in your library.


/* Filename: lib_mylib.c */
#include <stdio.h>
void fun(void)
{
  printf("fun() called from a static library");
}
We have created only one file for simplicity. We can also create multiple files in a library.
