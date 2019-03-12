# Banana DQN
This project is an assignment from the Udacity Deep Reinforcement Learning course. [p1_navigation](https://github.com/udacity/deep-reinforcement-learning/tree/master/p1_navigation) found [here](https://github.com/udacity/deep-reinforcement-learning#dependencies). The objective is to train a banana collecting agent using a DQN.


## Enviroment

##### Observation

Type: Box(37)

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction.

##### Actions
Type: Discrete(4)

The descrete actions represent the direction in wich the agent is moving.

##### Reward

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana.

## Installation and setup

##### 1.
For the dependancies to this project please follow the instructions from the assignment github [here](https://github.com/udacity/deep-reinforcement-learning#dependencies)

##### 2.
To install the unity environment  you'll need to download the right version for your pc, then drag the zip file into the project folder and unzip it.

Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)<br/>
Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)<br/>
Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)<br/>
Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)<br/>

##### 3.
Launch Jupyter notebook in the project folder.

## How to use
When running either of the notebooks make sure you have edited the PATH variable to your version of the unity Banana enviroment.

To train a model run the Training notebook.

To watch an agent perform run the Watching notebook.
