# Stochastic Multi-Armed Bandits for Wireless Channel Allocation

Python implementation of Upper Confidence Bound (UCB) algorithms for wireless channel allocation.

Developed as part of the **Reinforcement Learning and Dynamic Optimization** course.

## Overview

The project investigates how stochastic multi-armed bandit algorithms can optimize wireless channel allocation by balancing exploration and exploitation.

Two approaches are implemented and compared:

- **Case A – Standard UCB:** Treats each valid channel allocation as an independent arm.
- **Case B – Structured UCB:** Exploits the reward structure by learning individual user-channel rewards.

## Evaluation

The algorithms are evaluated through Monte Carlo simulations, comparing cumulative regret, regret per round, and cumulative reward against theoretical regret bounds.

## Implementation Tools

Python · NumPy · Matplotlib
