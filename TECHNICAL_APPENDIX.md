# Geometric distribution 

The geometric distribution is a discrete probability distribution that models the number of independent Bernoulli trials required to achieve the first success. Each trial has the same probability of success, and trials are independent of each other.

The geometric distribution requires three key conditions: independent trials, identical probability of success across all trials, and a fixed probability p where 0 < p ≤ 1. The standard notation uses p for the probability of success and q = 1-p for the probability of failure.

## * PMF *

![alt text](image-1.png)


where k is the number of failures 


## * CDF *

![alt text](image-2.png)

This represents the probability of achieving success within k trials. 

* Calculating the P-Value for a StreakTo determine if a player's max streak *
 * is "extraordinary" or just "luck," *
  calculated the probability of seeing a streak of at least that length.If $n$ is the total number of games and $k$ is the max streak, the expected probability of a streak of length $k$ occurring at least once is approximately:

![alt text](image-3.png)


  you can read this article for more information about the topic : https://arxiv.org/abs/1507.02935



<<<<<<< HEAD
# chi-square statistic and p-value


The Chi-square test of independence is a statistical hypothesis test used to determine whether two categorical or nominal variables are likely to be related or not.

![alt text](image-4.png)





$\chi^2$ : The Pearson Chi-Square test statistic.$O_i$: The Observed frequency (the actual number of wins/losses found in your chess dataset)


$E_i$ : The Expected frequency (the number of wins/losses we would expect to see if there was no relationship between the variables).

$\sum$ : The summation symbol, indicating that we calculate this for every "cell" in our contingency table (e.g., Win/Expert, Loss/Expert, Win/Non-Expert, Loss/Non-Expert) and add them together.


To determine the $p$-value, we must also calculate the degrees of freedom:

$$df = (r - 1) \times (c - 1)$$


Where $r$ is the number of rows and $c$ is the number of columns in your contingency table.
=======

# Shannon Entropy in Repertoire AnalysisIn 

this project, Shannon Entropy ($H$) is utilized to quantify the diversity and unpredictability of a player's opening repertoire. Unlike a simple count of unique openings, Entropy accounts for the probability distribution of those choices, identifying whether a player is a "specialist" (predictable) or a "generalist" (varied).

1. Mathematical DefinitionThe entropy of a player's opening distribution is
2.
3. calculated as:  $$H(X) = -\sum_{i=1}^{n} P(x_i) \log_2 P(x_i)$$
4.
5. Where: $n$ is the total number of unique openings played.
6.
7. $P(x_i)$ is the probability (frequency) of choosing opening $i$.
8.
9. The result is measured in bits.2. Logical InterpretationLow Entropy ($H \approx 0$): Indicates high predictability. A player relies almost exclusively on one or two openings. Even if they know ten openings, if they play one of them 99% of the time, their entropy remains low.
10.
11. High Entropy: Indicates a balanced and diverse repertoire. The player distributes their games across many different systems, making them harder to "prep" against in a competitive environment.
12.
13. 3. Application to Chess Strategy
    4.
    5. Entropy is used to test the relationship between strategic volatility and performance. By calculating the entropy of experts vs. non-experts, we can determine if "mastery" correlates with a narrowing of focus (lower entropy) or an expansion of theoretical knowledge (higher entropy).
>>>>>>> e4e9fe6ccb3d673d36d71baebbe999885fb5a458
