# Self-Diving-with-Reinforcement-learning

"A. Marino, - Self driving using RL".  
Code based from https://github.com/nicknochnack  
For any questions or suggestions write to alexismarino0109@gmail.com

## Summary.

The repository provided showcases an illustrative implementation of a self-driving algorithm employing Reinforcement Learning techniques, utilizing the stable-Baselines3 library. This example serves as a practical demonstration of how RL algorithms can be applied to autonomous driving scenarios, enabling vehicles to learn optimal decision-making policies through interaction with their environment. By leveraging stable-Baselines3, a powerful RL library, this implementation offers a robust foundation for experimenting with the PPO-Reinforcement Learning algorithm for specific autonomous driving tasks. it is programmed using a Phyton  
https://stable-baselines3.readthedocs.io/en/master/

## Overview

### Action Space

###### If continuous there are 3 actions :

0: steering, -1 is full left, +1 is full right
1: gas
2: breaking

###### If discrete there are 5 actions:

0: do nothing
1: steer left
2: steer right
3: gas
4: brake

###  Observation Space

A top-down 96x96 RGB image of the car and race track.

## Run
- To run the algorithm,  create a folder Training containing 2 folders: Logs and Saved model
- Additionally, 2 trained models are loaded, one with 10k steps and another with 428k steps to test just loading the models.  
![image](https://github.com/fercho-0109/Self-Diving-with-Reinforcement-learning/assets/40362695/596d7dcd-090c-4c59-adc4-306dca4eea99)

