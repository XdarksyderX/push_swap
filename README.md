# Push_swap

## Overview
`push_swap` is a complex algorithmic project focused on sorting data on stacks. The goal is to sort data on a stack with a limited set of operations and in as few moves as possible. This project is a part of the 42 school curriculum, challenging students to think critically about data structures and sorting algorithms.

## Features
- Efficient sorting algorithms implemented for stack-based data structures.
- A variety of operations like push, rotate, reverse rotate, and swap.
- Bonus part: `checker` program to evaluate the operations used for sorting.

## Compilation and Usage
### Requirements
- GCC compiler
- GNU make

### Compiling the Program
To compile the `push_swap` program, run:

```
make all
```

This command compiles the `push_swap` executable, which sorts the numbers provided to it.

### Compiling the Bonus Program
The bonus part includes a `checker` program, which checks the operations used by `push_swap`. To compile it, run:

```
make bonus
```

### Cleaning Up
To remove all object files and executables:

```
make fclean
```

To recompile everything:

```
make re
```

## File Structure
- `src/*.c` - Source files for the main algorithm and operations.
- `src/operations/*.c` - Operation functions like push, rotate, swap.
- `src/sort/*.c` - Sorting algorithms and their utilities.
- `src/checker/*.c` - Source files for the checker program (bonus part).

## Usage
After compiling, you can use the `push_swap` program by passing a list of integers. For example:

```
./push_swap 4 67 3 87 23
```

This will output a series of operations that sort the given integers.
