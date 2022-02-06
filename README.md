# PPO

PPO stands for Proximal Policy Optimization. It was introduced by OpenAI in this [paper](https://arxiv.org/abs/1707.06347) and was intended as an improvement over TRPO.

![](ppo.png)

Need to start with the right hyperparameters for good training, unlike policy gradient. But CartPole-v0 is a simple discrete action-space problem, so maybe it's not ideal?

<p align="center" style="border: 1px black solid;"><img src="returns.png"></p>
