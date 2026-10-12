

# RL Robot Navigation Using Q-Learning

## Project Overview

This project implements a grid-based robot navigation simulation using Reinforcement Learning. The robot learns to navigate from a starting position to a destination while avoiding obstacles using the Q-Learning algorithm.

## Objectives

* Implement a basic Reinforcement Learning algorithm.
* Train an agent to navigate a grid environment.
* Use rewards and penalties to guide learning.
* Visualize the learned route and training progress.
* Evaluate the agent's navigation performance.

## Technologies Used

* Python
* NumPy
* Matplotlib
* Q-Learning

## How It Works

1. A grid environment is created with a starting position, obstacles, and a goal.
2. The robot explores the environment by taking actions.
3. The Q-Learning algorithm updates action values using rewards and future estimates.
4. Exploration decreases gradually during training.
5. The trained agent follows its learned policy to reach the destination.
6. The program evaluates success rate and average steps and displays visualizations.

## Installation

Install Python, then install the required libraries:

```bash
python -m pip install numpy matplotlib
```

## How to Run

Run the following command from the project directory:

```bash
python main.py
```

## Results

In one training run, the robot achieved:

* Training episodes: 2,000
* Test episodes: 100
* Successful attempts: 100
* Success rate: 100%
* Average steps to goal: 8

Results may vary between runs because training includes random exploration.

## Visualizations

The program displays:

* The robot's learned route through the grid.
* A graph of the moving success rate during training.

## Learning Outcomes

* Understanding Reinforcement Learning fundamentals.
* Implementing Q-Learning in Python.
* Working with states, actions, rewards, and Q-tables.
* Evaluating a learned policy.
* Visualizing training and navigation results.

## Limitations

This project is a small grid-based simulation. It does not control a physical robot or demonstrate navigation in real-world environments.

## Future Improvements

* Test the agent on different grid layouts.
* Compare performance across different learning parameters.
* Experiment with larger environments and additional obstacles.

## Author

Bhargav Mehar
