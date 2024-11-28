Deep Q-Learning for CartPole
This project demonstrates how to use Deep Q-Learning (DQN) in PyTorch to train an agent to solve the CartPole-v1 environment from OpenAI Gym. The agent learns to balance a pole on a cart by interacting with the environment and optimizing a neural network-based Q-function.

Features
Implements a Deep Q-Learning algorithm with:
Replay Memory to store agent experiences for stable training.
Target Network to improve Q-value updates and reduce instability.
Epsilon-Greedy Exploration for balancing exploration and exploitation.
Uses a neural network with:
Two hidden layers, each with 64 neurons.
ReLU activation function for non-linearity.
Trains the model with Adam optimizer and Mean Squared Error (MSE) loss.
Visualizes:
Total rewards per episode over training.
Agent's performance in a test episode.
