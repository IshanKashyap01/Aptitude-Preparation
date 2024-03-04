# Formulae For Arrangements

1. According to the `m x n x p` rule of counting, if we have three tasks to perform
and:

    - There are `m` ways for the 1st

    - `n` ways for the 2nd

    - And `p` ways for the third

    - The total number of ways we can perform them **together** is `m x n x p`

2. If you have `r` distinct objects to place in `r` different places, then you can
do so in $r!$ ways

3. To place `n` objects with `r` identical objects in `n` distinct places:

    - Number of ways will be $n! \over r!$

## Questions

**Q.1** If there are 7 people to be seated together and 2 of them must always sit
together, how many ways can you arrange them?

- We will consider the two people (say A and B) as one person

- Then arrange these 6 people, while also arranging A and B within their joined
seats

- Therefore, according to the `mnp` rule, number of ways will be $6! \times 2!$

**Q.2** In how many ways can you arrange 16 players into a team of 11?

- First we can select 11 players out of the 16 in $^{16}C_{11}$ ways

- Then arrange them in $11!$ ways

- Therefore, according to the `mnp` rule, we can arrange the 16 players in a team
of 11 in $^{16}C_{11} \times 11!$ ways

***Note***: *This is also the formula for $^nP_r$ which is $n! \over (n - r)!$*
*which gives the number of ways to arrange `n` distinct objects in `r` places.*
*However, this formula doesn't work for any other case, therefore, using the*
*above way is recommended. One such case is just below*

**Q.3** In how many ways can you arrange 16 players in a team of 11 if the captain
is always on the team?

- Here, we will select 10 players from 15 but arrange 11 players

- Therefore, number of ways will be $^{15}C_{10} \times 11!$
