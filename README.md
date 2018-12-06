# AI-Learning-Models
Assignment 2 - Implementing Markov Decision Processes and Reinforcement Learning with Stochiastic Motion

Extracting Optimal Policies with known Models & Reward (Solving MDPs):
  - User inputs value for discounting future reward (gamma)
  - Using Bellman Equations calculate the values for all legal actions given the reward and transition models
  - Keep reapeating this value iteration process until the values for each action converges
  - Take the best value as the optimal Policy


Learning Most Optimal Actions without a known Model (Reinforcement Learning):
  - Through trial and error accumulate Q-values, choosing its current best Q-Value action
  - Choose an randomized action throughout this process epsilon times
  - Approximate Q-learning is then implemented by adding weights to each state
