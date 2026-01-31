# Decision-Making Algorithms: MCTS and MDP

This repository contains implementations and experiments on classical decision-making algorithms under uncertainty, focusing on **Monte Carlo Tree Search (MCTS)** and **Markov Decision Processes (MDPs)**.

The goal is to study algorithmic behavior, exploration–exploitation trade-offs, and policy optimality in controlled environments, rather than application-specific performance.

## Contents
  Python implementation of:
  - Monte Carlo Tree Search on a synthetic binary tree
  - Analysis and simulation of a stochastic circular MDP
  - Policy evaluation and Monte Carlo optimisation

 `Report.pdf`  
  Full problem formulation, mathematical derivations, experimental results, and discussion.

## Overview

### Monte Carlo Tree Search
MCTS is applied to a deep binary tree where leaf values depend on their distance to a hidden target leaf.  
The setup allows controlled evaluation of:
- search efficiency
- convergence to the optimal solution
- impact of the UCB exploration parameter

### Markov Decision Process
A finite MDP with circular state structure and stochastic transitions is analyzed.  
The project includes:
- transition and reward matrix construction
- optimal policy derivation under varying noise
- Monte Carlo optimisation of a parametrised stochastic policy
