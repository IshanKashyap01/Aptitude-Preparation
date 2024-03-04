# Selection Formulae For Sample Space

- The number of way we can choose any number from `n`, including no selections:

$$
\sum^n_{i = 0} {^nC_i} = 2^n
$$

- Therefore, ways to select the same without null selections will be $2^n - 1$

**Q.** There are 6 men and 4 women from whom a committee of 3 is to be formed.
How many ways can you make this committee if there should be at least 1 woman on
it?

- We can have a committe of all three women, or 2 women and 1 man, or 1 woman and
2 men:

  - For `W M M`: $^4C_1 \times {^6C_2}$

  - For `W W M`: $^4C_2 \times {^6C_1}$

  - For `W W W`: $^6C_3$

- After calculating for each case, we'll add them up
