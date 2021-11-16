# Challenge: Tennis Match

## The scoring system

1. The match starts with both player with the score of "love"
1. The scoring system of Tennis increases as follows: "15", "30", "40"
1. In the *simple scenario*, a player wins the game if he scores another time after "40"
1. If both players reach the score of "40", then they transition into a "deuce" state
1. When the players are in "deuce", if one of them scores he moves to "advantage"
1. If the player with "advantage" scores again, he wins the match
1. If there is one player in "advantage" and *the other* scores, both return to "deuce"

| Number of points | Score |
|:----------------:|:-----:|
|         0        |  love |
|         1        |   15  |
|         2        |   30  |
|         3        |   40  |
|         4        |  game |

## Objective

- Create a .NET Class Library that models a tennis match as described above
- Develop the solution using TDD and pair programming: be sure to explain your approach and the design of the solution
- Ultimately, implement a basic UI for the application - Web, WPF or Console
