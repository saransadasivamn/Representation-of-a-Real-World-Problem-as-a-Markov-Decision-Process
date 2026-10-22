# EXPERIMENT: 1

## Representation of a Real-World Problem as a Markov Decision Process (MDP)

### Title: Smart Irrigation System Using MDP

### 1. Aim

To implement a Smart Irrigation System using a Markov Decision Process (MDP) to control water supply based on soil moisture levels.

### 2. Problem Statement

A smart irrigation system automatically supplies water to plants based on soil moisture. It must decide whether to water the plants or wait based on the current soil condition.

Using MDP, the system can reduce water wastage and maintain proper soil moisture for healthy plant growth.

### 3. MDP Components

| Component       | Description                                     |
| --------------- | ----------------------------------------------- |
| States (S)      | Dry Soil, Moist Soil, Wet Soil                  |
| Actions (A)     | Water, Wait                                     |
| Transition (P)  | Probability of moving to another soil condition |
| Reward (R)      | Reward received after an action                 |
| Discount Factor | 0.9                                             |

### 4. Reward Function

| Condition    | Reward |
| ------------ | -----: |
| Moist Soil   |    +10 |
| Dry Soil     |     -5 |
| Wet Soil     |     -3 |
| Water Action |     +2 |
| Wait Action  |     -1 |

### 5. Algorithm

1. Start the program.
2. Initialize the soil states and actions.
3. Define transition probabilities.
4. Assign rewards to each state.
5. Select the current soil condition.
6. Choose an appropriate action.
7. Calculate the next state and reward.
8. Display the result.
9. Stop.

### 6. Python Program

```python
import random

print("SMART IRRIGATION SYSTEM USING MDP")
print("---------------------------------")

# States
states = ["Dry Soil", "Moist Soil", "Wet Soil"]

# Actions
actions = ["Water", "Wait"]

# Discount factor
```
