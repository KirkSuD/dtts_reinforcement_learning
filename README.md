# DTTS Reinforcement Learning

Train a double DQN reinforcement learning agent to play "don't touch the spikes".

DTTS is a little bit similar to Flappy Bird, but harder.

## Demo

RL agent gameplay:

![DTTS RL demo gif](https://raw.githubusercontent.com/KirkSuD/dtts_reinforcement_learning/master/demo.gif)

Sometimes it would score >50, but still sometimes dies instantly. I don't know why. The average score is ~30.

This is far from prefect. The agent can only score 50 when lucky, and it rarely eats the pine.  
But it probably already plays better than me, in terms of the score.

## How it works

The dtts.html is my little web game similar to the mobile game.  
I use tensorforce to train an agent, the environment is the game simulation written in Python.

## Files

- train.ipynb: my local testing notebook
- dtts_*.ipynb/xpynb: training notebook on Kaggle
- dtts_tensorforce_sim.ipynb: the most important notebook

I ignored 3 images because I don't own them. You can use any images.
