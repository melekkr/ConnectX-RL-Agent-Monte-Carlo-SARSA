# ConnectX-RL-Agent-Monte-Carlo-SARSA

This repository contains the implementation of **Reinforcement Learning (RL) agents** for the **ConnectX** game. The agents are trained using two different algorithms:
- **Monte Carlo First-Visit Agent**
- **SARSA(λ) Agent**

## Project Overview

The primary goal of this project is to implement reinforcement learning algorithms and train intelligent agents to play the ConnectX game effectively. The project focuses on developing and evaluating two types of RL agents using the **Monte Carlo** method and **SARSA(λ)** algorithm.

### Key Features:
- **Monte Carlo First-Visit Agent**:
  - Uses Monte Carlo method to update Q-values based on cumulative rewards.
  - The agent is trained using an epsilon-greedy policy against random and Negamax opponents.
  - Tracks rewards, visualizes gameplay, and extracts optimal policies.

- **SARSA(λ) Agent**:
  - Implements **Eligibility Traces** to improve learning efficiency using the SARSA algorithm.
  - Trains against Negamax opponent to refine strategies.
  - Evaluates performance by extracting learned strategies and optimal actions.

## How to Use

### Prerequisites
Ensure you have Python and the required dependencies installed.

1. **Clone the repository**:
   ```bash
   git clone https://github.com/melekkr/ConnectX-RL-Agent-Monte-Carlo-SARSA.git
