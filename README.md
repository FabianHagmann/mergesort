# mergesort
custom implementation of mergesort in C using recursively forked child processes

### Description

A detailed description of the functionality can be found at [forksort_td.pdf](forksort_td.pdf)

The forksort programm reads the input, that has to be sorted, from stdin. After successful completion the programm writes the sorted input lines to stdout.

If any error occures when managing resources or child processes the program terminates with `EXIT_FAILURE`, otherwise with `EXIT_SUCCESS`.

### Synopsis

```
  forksort
```
