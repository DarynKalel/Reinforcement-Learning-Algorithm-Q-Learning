# Reinforcement-Learning-Algorithm-Q-Learning
Building a Q Learning Reinforcement Algorithm for game play. Training performed on the FrozenLake game.

Goal of the agent is: To navigate through the frozen lake and find the goal without falling to the holes.

There are:

16 states 1 per square
4 possible actions (LEFT, RIGHT, DOWN, UP)
4 different types of blocks (S-start, F-frozen, H-hole, G-goal)

Picking an action
We can pick an action using one of two ways:

Pick an action randomly
Pick based on the current Q-Table to find the best action
Epsilon - variable that tells us a probability of selecting a random action. Epsilon's value starts offvery high and slowly decrease as the agents learns more about the environment
