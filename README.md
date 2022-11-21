# clobber-mcts
 This project aims to test Monte Carlo Tree Search methods on the clobber game

The project is implemented in Python3 on Google colab. In the main notebook, a 'Move' class and a 'Board' class contain all the functions needed to play a game. I created two main functions :
- A playNRandomGames($N, $algo) function that simulates successively $N consecutive games of a random policy against a computer which plays according to the algorithm $algo (UCT or nested UCT). For each game, the function outputs the final board and the result.
- A playAgainstComputer($algo) function that enables the user to play one game against a computer which plays according to the algorithm $algo.

Have fun !
