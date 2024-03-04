# Distribution of Identical Objects

- We can distribute `n` identical objects to `r` people (including no distributions
i.e. 0) as:

$$
^{n + r - 1}C_{r - 1}
$$

**Q.1** In the equation $x + y + z = 20$ where $x, y, z \in N$, in how many ways
can you distribute 20 to the given variables?

- Here, we cannot have a 0 value for any of them as they're all natural numbers

- Therefore, we'll first distribute 1 to each and have 17 left

- Then, we'll distribute the 17 using the above formula

- $^{17 + 3 - 1}C_{3 - 1} = {^19C2} = 171$

- Therefore, there are 171 ways to distribute 20 over three natural numbers

**Q.2** For the equation $A + B + C = 20$ where $A \ge 3, B \ge 5$, in how many
ways can you distribute to the given variables?

- Similar to the above question, our `n` will be $20 - (3 + 5) = 12$

- Therefore, the answer will be $^{12 + 3 - 1}C_3 = {^14C_2} = 91$
