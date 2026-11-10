# push_swap

An algorithm exercise from 42: sort a list of integers using two stacks and a restricted set of operations, while trying to minimise the number of instructions.

## Build and run

```bash
make
./push_swap 4 2 3 1
```

The program prints the stack operations needed to sort the input. This repository also contains checker binaries and a `make test` target for experimenting with random input.

```bash
make test size=10
```

The test target uses command-line utilities such as `shuf` and is geared towards a Linux environment.

## Code

- `src/main.c`: program entry
- `src/sort.c`: sorting strategy
- `src/move.c`: stack operations
- `src/utils.c`: supporting functions
- `libft/`: C utilities

## What I learned

Choosing an algorithm here was not only about correctness; the number of operations matters. It was good practice in balancing simple logic with measurable performance.
