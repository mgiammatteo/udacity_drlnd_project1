# Udacity DRL nanodegree Project 1: Navigation
In this project, we train an agent to navigate, and collect yellow bananas, in a large, square world, provided by a Unity Machine learning agent. More information on the Unity ml-agents can be found [here](https://github.com/Unity-Technologies/ml-agents).

## Project Details
The agent interfaces to a unity environment which is characterised by the following features:

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:
* 0 - move forrward.
* 1 - move backward.
* 2 - turn left.
* 3 - turn right.

The task is episodic, and in order to solve the environment, your agent must get an average score of +13 over 100 consecutive episodes.

### Code structure
The code is structured as follows. The deep rl agent is trained within **Navigation.ipynb**. The agent is imported from the **agent.py** module. This latter approximates the action value function via a neural network define din **model.py**.

## Getting Started
In cell 2 of Navigation.ipynb we import the Unity environment. This is provided by the udacity remote server. For a local installation of the Unity ml-agents, pelase refer to the following two source:
* [Linux, Mac](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Installation.md)
* [Windows 10](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Installation-Windows.md)

## Instructions
This is a jupyter notebook project. To run the code and train the deep reinforcement learning agent, you simply execute each of the cells in **Navigation.ipynb**. After training, the average socre per hundred episods will be displayed.
Note: To build your own Unity environment please refer to the following [link](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Getting-Started-with-Balance-Ball.md).