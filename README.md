# Reinforcement Learning Repo
This repo contains my implementations of various reinforcement learning algorithms.

## Structure
The repo is structured as follows:
```
src
├─── Flappy Bird Neat
├─── Mario AI
├─── OpenAI Gym
├─── PPO
└─── Q-Learning
```
Each folder contains a README.md file that explains the implementation of the algorithm.

## Algorithms
### Q-Learning
Q-Learning is a model-free reinforcement learning algorithm. It learns the optimal action-value function Q∗(s,a) for a given MDP. It does not require a model (hence the connotation model-free) of the environment, and it can handle problems with stochastic transitions and rewards, without requiring adaptations.

### PPO
Proximal Policy Optimization (PPO) is a family of first-order methods that can be used for policy optimization. It is an on-policy, model-free reinforcement learning algorithm which can be used for both continuous and discrete action spaces. PPO is a policy gradient method which is a class of methods that directly optimize the policy function itself.

### OpenAI Gym
OpenAI Gym is a toolkit for developing and comparing reinforcement learning algorithms. It supports teaching agents everything from walking to playing games like Pong or Pinball.

