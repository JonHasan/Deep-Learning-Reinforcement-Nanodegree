For this Project, you will be working with the Tennis(https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#tennis) Environment 

In this environment, two agents are hitting a ball over a net. If an agent hits the ball over the net, a score of +.01 is rewarded. If the ball is hit out of bounds or if an agent misses, the reward is decreased by -.01. 

The state space has 8 variables. These variables correspond to the position and velocity of the ball and the racket. Each agent receives its own set of observations. This then results in an action space of size 2. This is the movement towards or away from the net. 

The task is episodic, in order for the environment to be considered solved, agents must score +.5 over a range of 100 episodes. Specifically, each agent received an undiscounted reward after each episode and then the maximum of those two values is returned.

Once the average reaches .5, the environment will be considered solved. 

Feel free to make changes to the hyperparameters and neural network model. Since this is a multi agent problem, instability issues can be a problem. Slight deviations away from optimal hyperparameters can lead to devestating results. Keep this in mind as you progress with the project. 

### Getting Started

1. Download the environment from one of the links below.  You need only select the environment that matches your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86_64.zip)
    
    (_For Windows users_) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

    (_For AWS_) If you'd like to train the agent on AWS (and have not [enabled a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md)), then please use [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Linux_NoVis.zip) to obtain the "headless" version of the environment.  You will **not** be able to watch the agent without enabling a virtual screen, but you will be able to train the agent.  (_To watch the agent, you should follow the instructions to [enable a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md), and then download the environment for the **Linux** operating system above._)

2. Place the file in the DRLND GitHub repository, in the `p3_collab-compet/` folder, and unzip (or decompress) the file. 

### Instructions

Follow the instructions in `Tennis.ipynb` to get started with training your own agent! 

