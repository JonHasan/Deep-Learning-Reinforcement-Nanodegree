For this Project, you will be working with the Tennis(https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#tennis) Environment 

In this environment, two agents are hitting a ball over a net. If an agent hits the ball over the net, a score of +.01 is rewarded. If the ball is hit out of bounds or if an agent misses, the reward is decreased by -.01. 

The state space has 8 variables. These variables correspond to the position and velocity of the ball and the racket. Each agent receives its own set of observations. This then results in an action space of size 2. This is the movement towards or away from the net. 

The task is episodic, in order for the environment to be considered solved, agents must score +.5 over a range of 100 episodes. Specifically, each agent received an undiscounted reward after each episode and then the maximum of those two values is returned.

Once the average reaches .5, the environment will be considered solved. 


Feel free to make changes to the hyperparameters and neural network model. Since this is a multi agent problem, instability issues can be a problem. Slight deviations away from optimal hyperparameters can lead to devestating results. Keep this in mind as you progress with the project. 



