# Stock Market Simulation & Reinforcement Learning
In this project I built with a partner a Stock Market Simulation Environment using Reinforcement Learning (RL)!
Project Overview:
We created an OpenAI Gym-compatible stock trading environment and trained an RL agent to make data-driven trading decisions. 

The project spanned two phases:
Part 1: Basic environment with discrete actions (Buy/Sell/Hold) and single-share trading.
Part 2: Extended to support shorting option to give the agent a chance to profit from also downs

Key Components:
* Market Simulation: Realistic OHLC price data, commissions, and position tracking.
* RL Agent: DQN (Deep Q-Network) with 1D convolutions to analyze price trends.
* Reward Engineering: Profit-focused
* Validation: Rigorous testing on unseen market data to prevent overfitting.

Challenges & Learnings:
-Solved relative profit calculation issues when scaling to shorting.
-Balanced exploration vs. exploitation using epsilon-greedy decay.

Results:
Our agent learned viable strategies, achieving consistent profits in both environments.
This project was a deep dive into RL for finance, from environment design to real-world constraints.
