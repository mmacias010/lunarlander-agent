# lunarlander-agent
Deep Q-Learning implementation for Lunar Lander with Experience Replay. Comparative study of reward shaping and exploration strategies. CS 4320 Reinforcement Learning final project.
# Deep Q-Learning for Lunar Lander 

A comprehensive implementation of Deep Q-Networks (DQN) with Experience Replay for OpenAI Gymnasium's Lunar Lander environment. This project explores and compares multiple reinforcement learning techniques including potential-based reward shaping and alternative exploration strategies.

## Project Highlights

- **Baseline DQN**: Successfully solves Lunar Lander in 564 episodes (score: 200.06)
- **Experience Replay Buffer**: Breaks temporal correlations for stable learning
- **Function Approximation**: 2-layer neural network with target network
- **Comparative Analysis**: Evaluates reward shaping and linear epsilon decay
- **Detailed Results**: Training curves, performance metrics, and analysis

## Key Findings

Our experiments revealed that baseline DQN hyperparameters are remarkably well-tuned:
- Exponential epsilon decay (0.995) proved optimal
- Reward shaping created suboptimal local maxima (score: 129.26)
- Linear epsilon decay explored too long (score: 53.15)

Demonstrates that not all "improvements" help - negative results provide valuable insights into RL algorithm design.

## Tech Stack

- **Python 3.12**
- **PyTorch** - Neural network implementation
- **Gymnasium** - RL environment
- **Box2D** - Physics simulation
- **Matplotlib** - Visualization



Trained and evaluated three approaches:
1. Baseline DQN with exponential epsilon-greedy
2. Potential-based reward shaping
3. Linear epsilon decay schedule

Full analysis and training curves included in repository.


---


Comparative study of DQN techniques for continuous control. Implements Experience Replay, reward shaping, and exploration strategies on Lunar Lander-v3.

DQN agent that solves Lunar Lander in 564 episodes. Complete implementation with comparative analysis of reward shaping and exploration strategies.
