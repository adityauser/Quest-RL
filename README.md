# Quest-RL
Analyzing result obtained with quite different Reinforcement Learning algorithms.

## The Quest
With just a few changes in hyperparameters, the convergence of Q-networks dramatically changes, in this quest we will analyze this on different algorithms.
The experiment shows how strange Deep Reinforcement Learning is

## Elements
I have used Q-Learning with Prioritized Replay and Duel Q Networks(DDQN) <br>
**I haven't used the following methods in the algorithm which I have implemented in the miscellaneous section.**<br>
The agent will run on different hyperparameter setting for gamma and epsilon
For each hyperparameter setting, I have run experiment 3 times
I will be using OpenAI gym CartPole-v1 environment

## Overview 
The experiment is done over three different models (Phase 1, Phase 2 and Phase 3)
The experiment is done over nine epsilon_decay setting and five gamma setting, i.e. 9x5 settings
Each setting is tested three times

Running each phase took 13hours on my i5 7th Gen laptop

Go through each Phase : <br>
<a href="https://github.com/adityauser/Quest-RL/tree/master/Phase1">Phase 1</a><br>
<a href="https://github.com/adityauser/Quest-RL/tree/master/Phase-2">Phase 2</a><br>
<a href="https://github.com/adityauser/Quest-RL/tree/master/Phase-3">Phase 3</a><br>


## Miscellaneous:
* Small scale implementation of **Maximum Entropy Deep Reinforcement Learning** : <a href="https://github.com/adityauser/Quest-RL/tree/master/Soft Q Learning">Soft Q-Learning</a>
* Implementation of **Categorical Distributional DQN** : <a href="https://github.com/adityauser/Quest-RL/tree/master/Distributional-RL">C51</a>

## Personal Attachment : 
I did all this thing in Summer'18, since then I'm a big fan of Reinforcement Learning. I love analyzing the result, finding patterns and building possible explanations.



My code is inspired from  <a href="https://github.com/keon/deep-q-learning">keon_deep-q-learning</a>
