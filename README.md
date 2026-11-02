# Stochastic Multi-Armed Bandits for Wireless Channel Allocation

Python implementation of Upper Confidence Bound (UCB) algorithms for wireless channel allocation, developed as part of the **Reinforcement Learning and Dynamic Optimization** course.

## Overview

The project studies how UCB algorithms can learn to allocate wireless channels to users, balancing exploration of different channel assignments with exploitation of those offering higher rewards.

Two approaches are considered:

- **Case A – Standard UCB:** Each possible channel allocation is treated as a separate arm.
- **Case B – Structured UCB:** The algorithm exploits the structure of the problem by learning the rewards of individual user-channel pairs.

## Evaluation

The two approaches are evaluated through Monte Carlo simulations, comparing their cumulative regret, average regret over time, and cumulative reward. The results are also compared against theoretical regret bounds.

## Tools

Python · NumPy · Matplotlib
