# Phase 1

In the 1st phase, I tried to manipulate the reward function, and I have the basic idea of <a href="https://arxiv.org/abs/1509.06461">Double Q-Network</a> and <a href="https://arxiv.org/abs/1511.05952">Prioritized Experience Replay</a>, so I tried to implement both of them and messed the code which leads to some compelling observations. <a href="https://github.com/adityauser/Quest-RL/blob/master/Phase1/Phase1.ipynb">here</a>
I have also uploaded a <a href="https://github.com/adityauser/Quest-RL/tree/master/Phase1/Models">model</a> of each agent, the name of the model is in the format GxEDytrailz.h5, where :
* x = value of gamma
* y = value of epsilon_decay
* z = trail number (3 trails for each setting of hyperparameters)

## Problems in Phase1

* The agent is getting a negative reward after completing the episode, which is fine if the agent didn't live for 500 timesteps but even after completing the episode successfully agent was getting a negative reward of -10, this doesn't allow the Q-values to converge.
* Double Q-Network is not adequately implemented, prev_model and model is pointing to the same object and after every timestep model is copied to prev_model which is very poor implementation of Double Q-Network even due to this model is training slowly.
