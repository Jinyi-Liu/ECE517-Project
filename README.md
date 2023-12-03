# ECE 517 Reinforcement Learning Project
This repository is the project to ECE517 Reinforcement Learning (Fall 2023).

## Problem Statement
<!-- A supplier makes a contract with the platform. The supplier is the agent in the project.

At each time $t$, the supplier decides $(w_t,q_t)$ where $w_t$ is the wholesale price and $q_t$ is the quantity to be shipped to the platform. The lead time is $1$.  -->
An agent faces an uncertain demand. The state of the agent is the inventory level $I_t$. The agent can take an action to order more inventory, that is, the action $a_t$ is the quantity to be ordered at time $t$ and the lead time is $1$. 

The update of the state is 