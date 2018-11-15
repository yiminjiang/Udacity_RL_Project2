# Udacity_RL_Project2,

Project 2 of Udacity Deep Reinforcement Learning,

Project Details

In this environment, a double-jointed arm can move to target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of your agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.
state size: 33

Getting Started:
To run the code, you need to have PC Windows (64-bit) with Anaconda with Python 3.6 installed.

To download Anaconda, please click the link below:

https://www.anaconda.com/download/

Clone or download and unzip the DRLND_P2_Continuous_Control folder.

Download by clicking the link below and unzip the environment file under DRLND_P2_Continuous_Control folder

https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86_64.zip

Download by clicking the link below and unzip the ml-agents file under DRLND_P2_Continuous_Control folder

https://github.com/Unity-Technologies/ml-agents/tree/0.4.0b


Dependencies :
To set up your Python environment to run the code in this repository, follow the instructions below.

Create (and activate) a new environment with Python 3.6.
conda create --name drlnd python=3.6
activate drlnd
Install Pytorch by following the instructions in the link below.

https://pytorch.org/get-started/locally/

Then navigate to P1_Navigation/ml-agents-0.4.0b/python and install ml-agent.

pip install .
Install matplotlib for plotting graphs.

conda install -c conda-forge matplotlib
(Optional) Install latest prompt_toolkit may help in case Jupyter Kernel keeps dying

conda install -c anaconda prompt_toolkit 

Run the code
Open Continuous_Control.ipynb in Jupyter and press Shift+Enter to run the first cell to import all the libraries.


Train an agent
Run the cells which contain the "dppg" function.


The environment is considered as solved when the average score of last 100 eposides is greater than 30.0

How to run the code: open Continuous_Control.ipynb in jupiter and execute the code section by section.

Saved model files: check_pt_actor.pth and check_pt_critic.pth
