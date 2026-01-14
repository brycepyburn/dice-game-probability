### Probabilistic Analysis of Rank-Order Ties in a 4-Player Dice Game

**Background**
In a class project in which my group designed a board game, a case arose in which the game state was mathematically equivalent to the following scenario:

Players A, B, C, and D each roll a fair 6-sided die until they roll a 5 (selection of 5 as the target is arbitrary), recording the number of attempts it takes them to do so. The "loser" of the game is the player that requires the most attempts to roll a 5.

Our game did not intend to allow for there to be multiple "losers," so I wanted to calculate the probability of this occurring. 

**Methodology**
I opted to find the probability of every possible distinct game outcome and sum the relevant odds to find the chance of a tie. This allowed me to "check" my math by showing the sum of all cases is 1.

**Findings**
* 8 structurally distinct game outcomes
* ~8.6% tie probablity
* Average winning count: 1.9 rolls taken
* Average losing count: 11.9 rolls taken

**Repository Contents**
* [Worked Problem](Probability-Calculation.pdf)
* [Simulation] (Coming soon)

[⬅️ Back to My Portfolio](https://brycepyburn.github.io/)
