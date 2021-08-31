# Reinforcement-Learning-for-E-Commerce-Q-Learning-in-Action-

Reinforcement Learning is implemented in python from scratch. The robot will be trained using Q-Learning. It will know nothing about the environment initial. It doesn’t even know that there is a destination where it has to reach. It will figure out everything over a lot of episodes using Q-Learning.

Let's consider a pick and place robot in an E-Commerce store warehouse. We will give the location of an object, which will also be the starting location of the robot and from there it will find the best path to carry the object to the packaging area. There are obstacles in the path and there is going to be a penalty (negative reward) if the robot bumps into the obstacle. Also it has to reach the packaging area in minimum amount of time, so there is a very small negative reward for every step it takes.

A full description of the code and background of the project can be found in my medium article at at https://ashutoshmakone.medium.com/reinforcement-learning-8-pick-and-place-robot-in-an-e-commerce-store-warehouse-i-e-78d7af7e60c8
