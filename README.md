# Process-Scheduling-using-RL
This was done as a project component for Distributed Operating System course during my Masters.

Implemented a Deep Q model in training an  agent to effectively schedule jobs in an operating system environment using the Scheduler environment defined with the help of Gym library.
The Scheduler environment is based on the following implementation: https://github.com/TimeTraveller-San/JobSchedulingRLenv
The repository has already defined all the properties of the environment and how they can be customised.

We implemented a simple neural network with 3 hidden layer with #nodes in order : [128, 64, 32]. Finally an output layer, the size of the action space of the environment.
A sample output of the environment after around 50 episodes is uploaded as the 'states' image. The expanation of the arrangement of the image can be understood from the original repo of the environment.

The iPython notebook contains the implementation of a basic DQN agent, designed for training.
The weights of the model uploaded is a sample and not completely trained.
