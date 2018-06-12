# [Distral: Robust Multitask Reinforcement Learning](https://arxiv.org/abs/1707.04175)

##### TLDR

Presenataion – https://www.youtube.com/watch?v=scf7Przmh7c

###### How it looks:
![alt text](./1707_distral/f1.png)

###### Objectvive:

![alt text](./1707_distral/objective.png)

###### Intuition:
We try to learn one common policy for several different levels of the game (simulation, etc). So we add additional regularization term (c<sub>KL</sub>) to get our level-policy close to common one. (Similar idea to PPO one?)