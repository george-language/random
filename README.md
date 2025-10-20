# `random`
```shell
glang install random
```

**Generate random numbers in GLang**

```
fetch random

bark(random_number()); # random number
bark(random_range(0, 100)); # random number in the defined range
```

## Supported Generators

| Function             | Output                                                                        |
| -------------------- | ----------------------------------------------------------------------------- |
| `random_number()`    | Gives a random number with no specified range by using the LCG algorithm.     |
| `random_range(a, b)` | Gives a random number between `a` and `b` using the `random_number` function. |
