### The Environment

For this project, you will work with the Reacher Environment. 

In this environment, an arm with two joints can move to desired locations. A reward of +.1 is provided for each step that the agents hand is in the goal location. Thus the goal of the agent is to maintain its position at the target location for as many time steps as possible. 

Observation space has 33 variables that correspond to position, rotation, velocity and angular velocities of the arm. The action space has four numbers thatcorrespond to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1. 


There are two environments for this challenge. The first version has a single agent and the second one has 20 agents, each with its own copy of the environment. The second environment is good for algorithms such as PPO, A3C and D4PG that use copies of the same agent to distribute the task of gathering experience. 

### Solving the Environment 

The project only needed to be solved with one of the two environments. 

### Option 1: Solve First Version
The task is episodic, and in order to solve the environment, your agent must get an average score of +30 over 100 consecutive episodes. 

## Option 2: Solve Second Version

This one is slightly different. One needs to stabilize the average score over all the agents. 

After each episode, rewards are added up and then averaged. 

Environment is considered solved, when the average score over all agents over 100 episodes is at least 30. 


### Running the files

To run the files, simply download the files and run the jupyter-notebook command in the file directory that houses the files. 
