# Analysis of Algorithms

## Exercise I

a) `O(n)` => As the value of n increases the number of iterations through the while loop increases at the same rate, i.e. linearly.

b) `n * n * n * constant = n^3 * constant = n^3 = O(n^3)` => Each `for` loop has an algorithmic complexity of O(n) except the last `for` loop. The last `for` loop has an algorithmic complexity of O(1) since it will only ever run 9 times.

c) `n = O(n)`

## Exercise II

Pseudocode:

```
initialize a boolean for whether the egg has broken or not

set the floor f to 0

while the egg has not broken:
    drop the egg

    if the egg breaks:
        store that the egg broke and set the boolean value to true
    else:
        go up one floor
```

The algorithmic complexity of this is `O(n)`, as the floor number increases by 1 only 1 loop is required.
