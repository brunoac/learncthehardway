# make ex1
* Does the file ex1 exist already?
* No. Ok, is there another file that starts with ex1?
* Yes, it's called ex1.c. Do I know how to build .c files?
* Yes, I run this command cc ex1.c   -o ex1 to build them.
* I shall make you one ex1 by using cc to build it from ex1.c.

# Makefiles basics
* Make automatically assumes there's a file called Makefile and will just run it.
* Always use tab for identation
* How to create a target. For example:
```
CFLAGS=-Wall -g

clean:
        rm -f ex1
```

# -g option
* Tells the compiler to store symbol table information in the executable
* [How Does The Debugging Option -g Change the Binary Executable?](http://stackoverflow.com/questions/89603/how-does-the-debugging-option-g-change-the-binary-executable)

# System table
Symbol table is a data structure used by a language translator such as a compiler or interpreter, where each identifier in a program's source code is associated with information relating to its declaration or appearance in the source.
