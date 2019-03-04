# Papers insights

## Real-Time Bidding with Multi-Agent Reinforcement Learning in Display Advertising
https://arxiv.org/pdf/1802.09756.pdf

Coordinated agents work better - common objective function as a whole. Coordinate to reach higher cooperative goal.
Reward: related to revenue/ROI. Losed acuction -  no reward
RTB as Stochastic game
Large number of merchangs clusterd in agent
Deterministic policy gradient 

## Deep Reinforcement Learning for Sponsored Search Real-time Bidding

https://arxiv.org/pdf/1803.00259.pdf

Sponsored search -- different than RTB (ranked)
Aggregation per hour
Cooperative rewards also used (public cooperative objective)
DQN


# Packages/Frameworks

## Axelrod
Python library for basic game theory
https://axelrod.readthedocs.io/en/stable/

## RLlib
Ray -- flexible, high-performance distributed execution framework. (Uses gym)  
https://bair.berkeley.edu/blog/2018/12/12/rllib/
https://ray.readthedocs.io/en/latest/index.html
https://ray.readthedocs.io/en/latest/rllib.html
https://ray.readthedocs.io/en/latest/rllib-env.html#multi-agent-and-hierarchical
https://github.com/ray-project/ray/blob/master/python/ray/rllib/examples/multiagent_cartpole.py

## Gym
Openai -- toolkit for dev RL algorithms
https://github.com/openai/gym
https://github.com/openai/multiagent-particle-envs

## ~~Dopamine by Google~~ --  No support multi-agent as-is. https://github.com/google/dopamine/tree/master/docs
