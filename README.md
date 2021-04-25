# CS370
For this project I was given code that contained the definition of the environment map as well as the objective of the game. My goal was to implement a reinforcement algorithm, namely Q-learning, to allow an agent named “pirate” to navigate an environment it had no knowledge of toward a “treasure.” This objective was accomplished by generating a Q-table that would tell the agent what action had the highest probability of reward for every conceivable state. A reward was given to the agent when it reached the treasure, so the algorithm naturally produced the most efficient paths toward the treasure. To improve space efficiency a neural net was used to approximate the Q-table with a high degree of certainty. \
\
When working on this project and any others like it, it’s important to consider the ethical implications of deep learning algorithms. Here, the ethical implications are fairly obvious, as the application is purely for entertainment and doesn’t take any user input. In future projects that have a heavier reliance on user data, it’s important to understand exactly how it is used in the algorithm you are utilizing to produce a solution. As a computer scientist, it is of vital importance that I am not leveraging user data in a way that is exploitative. The goal of every project should be to benefit others and to stop unfair treatment. Bias can be a particularly nasty byproduct of careless data analysis that can have real consequences on the user’s experiece and even quality of life. 

