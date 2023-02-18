<p align="center">
  <img src="http://www.holbertonschool.com/holberton-logo.png" alt="Holberton School logo">
</p>

# Simple Shell project 0x16.c - Sodash -

This is a simple UNIX command interpreter based on bash and Sh.

## Overview

**Sodashy** is a sh-compatible command language interpreter that executes commands read from the standard input or from a file.

### Invocation

Usage: **Sodash** 
Sodash is started with the standard input connected to the terminal. To start, compile all .c located in this repository by using this command: 
```
gcc -Wall -Werror -Wextra -pedantic *.c -o sodash
./sodash
```

**Sodash** is allowed to be invoked interactively and non-interactively. If **sodash** is invoked with standard input not connected to a terminal, it reads and executes received commands in order.
