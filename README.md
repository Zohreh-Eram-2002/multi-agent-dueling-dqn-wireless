# multi-agent-dueling-dqn-wireless
# Multi-Agent Dueling DQN with Prioritized Experience Replay for Heterogeneous Wireless Networks

## Overview

This project implements a **Multi-Agent Deep Reinforcement Learning framework** for resource allocation in heterogeneous wireless networks.

The approach combines:

* Dueling Deep Q-Network (Dueling DQN)
* Double DQN
* Prioritized Experience Replay (PER)

to optimize power allocation across base stations.

---

## Problem Statement

Efficient power allocation in heterogeneous networks (HetNets) is a challenging optimization problem due to:

* Interference between cells
* Dynamic channel conditions
* Multi-agent interactions

This project models the problem as a **Markov Decision Process (MDP)** and solves it using deep reinforcement learning.

---

## Key Features

* Multi-Agent learning (one agent per base station)
* Dueling DQN architecture
* Double DQN target update
* Prioritized Experience Replay (PER)
* Custom wireless environment simulation

---

## Architecture

### Dueling DQN

The Q-value is decomposed into:

* Value function V(s)
* Advantage function A(s, a)

---

## Environment

A simplified heterogeneous network including:

* Macro Base Station (MBS)
* Pico Base Stations (PBS)
* Multiple devices and subchannels

---

## Experiments

### 1. Learning Rate Analysis

* Tested multiple learning rates:

  * 0.1
  * 0.01
  * 0.001
  * 0.0001

### 2. Algorithm Comparison

* DC-MA-DDQN (Dueling)
* DC-MA-DQN (Standard)

---

## Results

* Faster convergence with Dueling DQN
* Improved stability using PER
* Better reward optimization compared to standard DQN

---

## Future Work

* Incorporate realistic wireless channel models
* Extend to continuous action space (DDPG / PPO)
* Apply to 5G/6G network scenarios

---

## Author

Zohreh Eram

---

## ⭐ If you like this project

Give it a star on GitHub!
