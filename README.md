# Udacity_RL_Project2,

Project 2 of Udacity Deep Reinforcement Learning,

Project Details

In this environment, a double-jointed arm can move to target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of your agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.
state size: 33

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
