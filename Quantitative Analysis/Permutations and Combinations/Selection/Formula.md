# Selection Formula

- To select `r` people from `n`, the number of different ways we can do this is
given by:

$$
^nC_r = {n! \over{r!(n - r)!}}
$$

- Or we can manually come up with all formations but that brute force approach
won't work in most cases

- The ways of selecting `r` from `n` *idenctical objects* is **always 1**

**Q.1** There are 8 men and 6 women in the room. Every man shakes hand with every
woman. How many hand shakes happened?

- Number of handshakes will be $^8C_1 \times ^6C_1$

**Q.2** In a room full of people, everyone shook hands with each other. If there
were 153 hand shakes, how many people were there?

- Suppose there are `n` people in the room; we can find the number of handshakes
by finding the number of ways we can select 2 people from `n`

- $\therefore {^nC_2} = 153$, from here we can solve for `n` and find the number
of people in the room
