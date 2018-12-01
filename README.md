# Quest-RL
Analyzing result obtained with quite different Reinforcement Learning algorithms.

## The Quest
With just a few changes in hyperparameters, the convergence of Q-networks dramatically changes, in this quest we will analyze this on different algorithms.
The experiment shows how strange Deep Reinforcement Learning is

## Elements
I have used Q-Learning with Prioritized Replay and Duel Q Networks(DDQN)
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




My code is inpired from  <a href="https://github.com/keon/deep-q-learning">keon_deep-q-learning</a>
