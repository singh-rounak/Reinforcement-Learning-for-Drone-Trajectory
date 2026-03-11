<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/eba0e4fa-84bf-41e9-9df1-e0ea18011940" /># Autonomous Drone Trajectory prediction using Reinforcement Learning
![image alt](https://github.com/singh-rounak/Reinforcement-Learning-for-Drone-Trajectory/blob/develop/RE%20images/image1.png?raw=true)
## Project Overview

Autonomous drones are increasingly used in areas such as:

* Disaster response

* Aerial surveillance

* Environmental monitoring

* Delivery logistics

A major challenge is trajectory planning — determining the most efficient path for a drone to reach a destination while interacting with the environment.

Traditional algorithms rely on predefined rules or optimization methods.

This project explores a different approach:

Allowing the drone to learn the optimal trajectory through reinforcement learning.

The agent interacts with the environment, receives rewards based on its actions, and gradually learns the best flight strategy.

## Objective

Design an intelligent drone agent that:

* Learns the shortest path to the destination
* Avoids inefficient movements
* Improves trajectory performance through training episodes
  
![image alt](https://github.com/singh-rounak/Reinforcement-Learning-for-Drone-Trajectory/blob/develop/RE%20images/image3.png?raw=true)

## Learning Process

The drone follows a training cycle:

1. Initialize the environment grid

2. Start drone at initial position

3. Choose action (exploration vs exploitation)

4. Receive reward from the environment

5. Update Q-values

6. Repeat across many episodes


## Through this process the agent gradually converges to an optimal trajectory policy.

![image alt](https://github.com/singh-rounak/Reinforcement-Learning-for-Drone-Trajectory/blob/develop/RE%20images/image4.png?raw=true)

## WORKFLOW

Environment Setup
        ↓
State Representation
        ↓
Q-Learning Algorithm
        ↓
Reward Optimization
        ↓
Trajectory Learning
        ↓
Optimal Path Discovery

Applications of the Approach

![image alt](https://github.com/singh-rounak/Reinforcement-Learning-for-Drone-Trajectory/blob/develop/RE%20images/image2.png?raw=true)

Reinforcement learning based trajectory planning is widely used in:

• autonomous drones
• robotic navigation
• delivery drone systems
• UAV surveillance missions
• disaster monitoring

Modern research increasingly applies reinforcement learning to UAV navigation because it allows agents to learn optimal policies directly through environment interaction.
