# Gridworld

## Introduction

The rule is simple. Your agent/robot starts at the left-bottom corner(the ‘start’ sign) and ends at either +1 or -1 which is the corresponding reward. At each step, the agent has 4 possible actions including up, down, left and right, whereas the black block is a wall where your agent won’t be able to penetrate through. In order to make it more straight forward, our first implementation assumes that each action is deterministic, that is, the agent will go where it intends to go. For instance, when the agent decides to take action up at (2, 0), it will land in (1, 0) rather than (2, 1) or elsewhere. (We will add uncertainty in out second implementation) However, it the agents hit the wall, it will remain at the same position.

![1*S3oszDubmqzfuu2vRnn3yw](https://user-images.githubusercontent.com/111204401/184550890-c625224e-ead5-4d84-873c-0d6845a584f0.png)

## Methdology
* MDP
* SARSA
* Q learning

## Task

Dr.Davila has already explained the code of Gridworld in three method in his notebook. In this notebook, I will only introduce the calculation  of gridworld(mdp)
It is also very interesting.

Another version of code for gridworld mdp https://github.com/erikon/reinforcement-learning/blob/master/valueIterationAgents.py
Author:Leviwalsh

I also watched this video to know how the value iteration works.https://www.youtube.com/watch?v=14BfO5lMiuk&list=PLWzQK00nc192L7UMJyTmLXaHa3KcO0wBT&index=2
