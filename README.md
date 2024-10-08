# AI Learns To Play Snake

Welcome to the Snake AI project! This repository contains an implementation of a self-learning AI agent designed to play the classic Snake game. The agent is trained using Q-learning, a type of reinforcement learning, and leverages the PyTorch framework for neural network training and inference.



## Features

- **Reinforcement Learning**: Utilizes Q-learning to train the snake to play the game efficiently.
- **Deep Learning**: Implements a neural network with PyTorch to predict the best moves for the snake.
- **State Representation**: Captures the game state with relevant information for effective decision making.
- **Dynamic Training**: Continuously trains and improves the snake's performance over multiple game iterations.
- **Performance Tracking**: Plots scores and mean scores to visualize the training progress and performance improvements.

## Prerequisites

- **Python**: Programming Language
- **Anaconda**: Virtual Environment
- **PyTorch**: Training Neural Network through Reinforcement Learning
- **NumPy**: Numerical Operations
- **Pygame**: Game Development 
- **Matplotlib**: Plotting Training Graphs

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Youkta/AI-Snake-Pytorch.git
   cd snake-ai
   ```

2. **Create a virtual environment using Conda:**

   ```bash
   conda create -n pygame_env python
   ```

3. **Activate the virtual environment:**

   ```bash
   conda activate pygame_env
   ```
   
4. **Running the AI** 

   To start the AI agent and let it play the Snake game, enter the correct directory containing the files and run:
   
   ```bash
   python agent.py
   ```

## Repository Structure

- `agent.py`: Contains the Agent class that defines the AI agent and the Q-learning training loop.
- `game.py`: Implements the Snake game logic, including the game board, snake movement, and collision detection.
- `model.py`: Defines the neural network architecture and the training process using PyTorch.
- `helper.py`: Contains utility functions for plotting the training progress.
- `arial.ttf`: Arial font for rendering on display
- `snake_game_human.py`: The keyboard controlled version of the Snake Game
- `.gitignore`: Specifies files and directories to be ignored by git.
- `LICENSE`: License for the project.
- `README.md`: Readme file with brief summary and instructions regarding installation and running code

## Training Graph

   ![Figure_1](https://github.com/Youkta/AI-Snake-Pytorch/assets/152993509/a609d430-ebd1-4493-8308-c4bbbb1faed0)

## Possible Future Improvements

- Implement more advanced RL algorithms (e.g., Double DQN, Dueling DQN).
- Add more features to the game (e.g., obstacles, different levels).
- Improve the efficiency and performance of the training process.
- Feature to store the previous game’s performance and resume.
- Use NEAT algorithm instead of deep Q-learning for better learning.

