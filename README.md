## Big Data Research Project

The objective of this work is to develop an algorithm using model-free reinforcement learning, specifically Q-learning, to solve the 3D bin packing problem. The algorithm will be designed to maximize the volume utilization of the containers while taking into account constraints such as size limits, and handling irregularly shaped items and dynamic changes in the number of items and containers. The performance of the algorithm will be evaluated using different scenarios and compared with other existing approaches.

This repository contains final results of our Big Data Research Project on 3D Bin Packing with Deep Reinforcement Learning.
In the attached notebook we use the Jumanji environment to train a reinforcement learning agent to solve 3D Bin Packing Problem. The agent is trained using the DQN algorithm. The script creates a replay buffer and neural network, and uses them to train the agent. It also includes a function to flatten the observation data from the environment.

Here's a demo of the best items stacking we've achieved so far:

![213897391-693b783b-e9cc-4c4b-9ebc-6df1a3e115c5](https://user-images.githubusercontent.com/113067162/219979046-8b66a111-6789-4ae1-8ad0-e5c402e7752b.gif)


At the end of the file, the script throws an error, it is due to the fact that in this part of the code we run an endless loop in which items are added to the box. The error comes out because we end running.
