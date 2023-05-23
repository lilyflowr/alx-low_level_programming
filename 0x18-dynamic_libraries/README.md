# 0x18. C - Dynamic libraries

I learnt about what dynamic library is, how it works, how to create one and how it works. It also understood the differences between static and shared libraries.

## Function Prototypes


## Table of contents
Files | Description
----- | -----------
[libdynamic.so](./libdynamic.so) | C dynamic library containing the function definitions
[main.h](./main.h) | Header files containing the function prototypes
[1-create_dynamic_lib.sh](./1-create_dynamic_lib.sh) | It is a bash script that creates a dynamic library called liball.so from all the .c files that are in the current directory
[100-operations.so](./100-operations.so) | C dynamic library that contains C functions that can be called from Python
[random.so](./random.so) | C dynamic library to inject in a giga million program
[101-make_me_win.sh](./101-make_me_win.sh) | Bash script to inject the libmask.so library, using LD_PRELOAD, in giga million program
