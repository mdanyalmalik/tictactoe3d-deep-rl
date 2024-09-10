# Final Project: Reinforcement Learning for Tic Tac Toe

This is a course project submission for the course: Dynamic Programming and Reinforcement Learning (CS 6314) at Lahore University of Management Sciences.

## Overview

### Phase 1: 2D Tic Tac Toe (3x3 Grid) - Value Iteration Implementation

- **Objective:** Build an AI agent using value iteration to play 2D Tic Tac Toe on a 3x3 grid.

### Phase 2: 2D Tic Tac Toe (4x4 Grid) - Q Learning Implementation

- **Objective:** Construct an AI agent using Q learning to play 2D Tic Tac Toe on a 4x4 grid.

### Phase 3: 3D Tic Tac Toe (4x4x4 Grid) - Open-Ended AI Design Competition

- **Objective:** Develop an AI model for 3D Tic Tac Toe on a 4x4x4 grid, employing various approaches to create an optimal policy.
- The model used was an approximate version of Temporal Difference Learning, known as Neural Temporal Difference Learning.

## Training

- To train each model, please refer to the notebooks in the code section of the repository.

## Pre-trained Models

- For phase 1, the policy is available as a .pkl file. The code to load and use it is available in the notebook.
- For phase 2, the Q table is available as a .pkl file. The code to load and use it is available in the notebook.
- For phase 3, the latest trained model is available as a .pth file. The code to load and use it is available in the notebook.

## Results

### Phase 1

Evaluating the policies against a random opponent, our results were:

- Wins as X: 99.5%
- Draws as X: 0.5%
- Wins as O: 80.7%
- Draws as O: 19.3%

### Phase 2

The results we obtained (against a random player) were:

- Wins as O: 54.7%
- Draws as O: 24.9%
- Wins as X: 28.2%
- Draws as X: 39.8%

### Phase 3

![](https://i.imgur.com/ov4wXiT.png "Results Graph")

When played against the online version of the game [Tic Tac Toe 3D](https://www.mathsisfun.com/games/foursight-3d-tic-tac-toe.html), our agent was able to defeat the Easy bot but not the difficult bot. With enough training, it seems to be possible to defeat the latter as well.

## Credits

- Neural TD Implementation: [Temporal Difference Learning for the Game Tic-Tac-Toe 3D: Applying Structure to Neural Networks](https://www.ai.rug.nl/~mwiering/GROUP/ARTICLES/TTT3D_FINAL.pdf)
