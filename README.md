# Analysis of Different Methods of Optimising Play in Noughts and Crosses
This is the implementation of the noughts and crosses (also known as Tic-Tac-Toe) with four methods.
## Abstract
This project aims to apply advanced computational techniques to analyse and develop optimal strategies for the game of Knoughts and Crosses. By using various algorithms and machine learning approaches, we seek to identify the most effective decision-making processes for players, potentially leading to perfect play. The project will explore four methodologies: Minimax Algorithm, Reinforcement Learning (Q-Learning), Neural Networks, and Monte Carlo Tree Search, evaluating their performance and applicability to Knoughts and Crosses.

## Problem Statement
The project aims to design optimal strategies for Knoughts and Crosses using game theory to achieve Nash equilibrium, while also applying AI techniques like Q-learning and Neural Networks to learn winning strategies. The objective is to analyze and compare these approaches to understand their effectiveness in achieving optimal play.

## Methodology

### Minimax Game
Minimax Games are a fundamental concept in game theory, primarily used to analyze decision-making in competitive environments involving two players with opposing objectives. The goal of the minimax strategy is to minimize the possible maximum loss a player can incur, assuming that their opponent is playing optimally to maximize that loss.

### Monte Carlo Tree Search
Monte Carlo tree search (MCTS) is a heuristic search algorithm. Some notable examples. MCTS has an advantage in games with high branching factors because unlike minimax which needs a full game tree, MCTS can be configured to select a sufficiently optimal solution based on a partially constructed game tree. MCTS keeps statistics of each nodes and then applies the Upper Confidence Bound (UCB) algorithm to the node’s stats.

### Q-Learning
By using Q-Learning, the agent incrementally improves its strategy by exploring the game states, receiving rewards for favorable outcomes (winning, drawing) and penalties for unfavorable ones (losing). Over time, the agent learns the value of each move in a given game state, developing an optimal strategy that minimizes mistakes and increases the likelihood of victory.

The agents converge to a Nash equilibrium—a point where neither player has an incentive to deviate from their strategy, since any unilateral change would result in a lower payoff.
This means that after training:

- Player "X" and "O" have both learned their best possible responses to the other player's strategy.
- The game often results in a draw, which is the equilibrium outcome when both agents play optimally.
Thus, the Q-Learning process allows these rational agents to learn and adapt their strategies, eventually leading to Nash equilibrium where both players have no incentive to change their actions, ensuring stability in their gameplay strategies.

![image](https://github.com/user-attachments/assets/375c7fc2-8de5-4307-9bce-fd54fc1e191c)

### Deep Q Neural Network
