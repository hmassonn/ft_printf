# ft\_printf @ 42
Because I wanna stop of using putnbr and putstr

This project aims at rebuilding the printf library with basic functionality. I
tried to implement as much of the original as possible, and also have a few
extra things which I found to be rather useful.

Extra conversions:

| Name		| Conversion	| Example output	|
| --------- | ------------- | ----------------- |
| Binary	| b				| 00001001			|

## Compiling
Run `make` to compile the
library. Use it like you would use the `printf` function:

```c
int i;

i = 42;
ft_printf("value: %d\n", i);

// value: 42
```
