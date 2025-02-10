# Deep Q-Network (DQN) with Experience Replay

This repository contains an implementation of Deep Q-Network (DQN) with Experience Replay. The model was tested on three environments:
- **Grid World (Warehouse Robot)**
- **CartPole**
- **Lunar Lander**

The warehouse robot in the Grid World environment learned successfully, as indicated by its increasing cumulative reward. However, the CartPole and Lunar Lander environments faced challenges in convergence and learning.

## Features
- Implementation of **DQN with Experience Replay**
- Training and evaluation on multiple environments
- Logging of cumulative rewards to track learning progress

## Environments
### Grid World (Warehouse Robot)
A warehouse robot navigating in a grid world to optimize its movements. This environment successfully learned a policy, showing improvement in rewards over training episodes.

### CartPole
A classic reinforcement learning environment where a pole must be balanced on a moving cart. The DQN model struggled to learn a stable policy.

### Lunar Lander
A reinforcement learning task where a lander must be controlled to safely land on a designated pad. The DQN implementation had difficulty stabilizing training in this environment.

## Results
- **Grid World (Warehouse Robot)**: Successfully learned an optimal policy, leading to increased cumulative rewards over training.
- **CartPole & Lunar Lander**: Training was unstable, and the agent struggled to achieve consistent improvement.

## Future Improvements
- **Hyperparameter tuning** to improve learning in CartPole and Lunar Lander.
- **Use of Double DQN or Dueling DQN** for better performance.
- **Reward shaping** to help guide the agent in learning better policies.


