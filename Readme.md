# Reinforcement Learning Snake Game

## Overview

This repository contains my implementation of a Snake game using reinforcement learning. I built this project as part of my weekend project and to apply reinforcement learning concepts in a practical way. The goal is to teach an AI agent to play the classic Snake game using PyTorch and Pygame.

### Demo of project outcome



## Project Structure

The project is organized into several parts, with each part having its dedicated code file:

1. **Setting Up the Game**: In this section, I initialized the game environment, created the Snake, and set up the game mechanics. The code for this part can be found in the `snake_game.py` file.

2. **Training the Agent**: Here, I implemented the Q-learning algorithm and trained the AI agent. You can find the code for this part in the `model.py` file.

3. **Deep Q-Network (DQN)**: In this part, I introduced Deep Q-Networks (DQN) to enhance the agent's learning capabilities. The code for DQN implementation is in the `agent.py` file.

4. **Visualizing**: In this section,I implemented all the plotting and visualizing training scores and mean scores during the training of your reinforcement learning agent. Code can be found in the `helper.py` file

## To Run locally follow below instructions
### Pull the code

```bash
git clone https://github.com/Hemanth-Thaluru/reinforcement_learning.git
cd reinforcement_learning
```

### Create virtual environment

```bash
conda create -n snake_env python=3.7
```

### Activating the virtual env

```bash
conda activate snake_env
```

### Installing required packages

```bash
pip install -r requirements.txt
```

### Starting the project
```bash
python3 agent.py
```