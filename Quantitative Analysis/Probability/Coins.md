# Probability Questions Based on Coins

## Unbiased Coins

Suppose 3 coins are tossed together or one coin is tossed 3 times

### Sample Space Approach (Brute Force)

- You can build the sample space for the experiment as follows:

```list
HHH     THH HTH HHT     TTH HTT THT     TTT
```

- Now if we can answer the probability for any event such as $P(3H), P(2H), P(\ge 2H)$
etc.

- However, for larger test cases, this approach will become too cumbersome

## Formulaic Approach

- Alternatively, we can use the fact that the probability for one toss is 50-50

- Therefore, in case of multiple events, we can join each event logically with
`and/or`

- For instance, the probability for all three heads would be
$P(3H) = {1\over{2}}\times{1\over{2}}\times{1\over{2}}$ where $1\over2$ is the
probability of a head in one toss

- Or that of either exactly one head or three heads would be $P(1H | 2H) = P(1H) + P(3H)$

## Biased Coins

- In case of biased coins, you'll also be given the bias i.e. probability for heads
and tails

- However, due to the bias, you cannot build a sample space and hence, can only
use the alternate approach

- Instead of using $1\over2$ for the probability of both head and tails for a toss,
we will use the given bias
