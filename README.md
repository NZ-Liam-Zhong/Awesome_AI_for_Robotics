# Awesome_AI_for_Robotics
As ChatGPT and RT2 appears, many researchers start to do reseaches about AI for robotics. Many scholars have different names for it, including embodied AI, smart robotics, etc. I don't care what its name really is, I just want to share what I have learnt. Hope it helps!


## Tutorials & Slides
1. [Deep Reinforcement Learning slides by Sergey Levine CS 285 at UC Berkeley](https://rail.eecs.berkeley.edu/deeprlcourse/)
A very good slide to learn the basic concepts of reinforcement learning. Super clear. **Institution： UC Berkeley**



## Papers

### Reinforcement Learning
1.[HIQL: Offline Goal-Conditioned RL
with Latent States as Actions](https://proceedings.neurips.cc/paper_files/paper/2023/file/6d7c4a0727e089ed6cdd3151cbe8d8ba-Paper-Conference.pdf)
This paper introduces a new way to improve the performance of action-free offline reinforcement learning. Most of the time, when we want to do training in action-free offline reinforcement learning, we need to train a value network and use it to update a Q function network. However, the authors in this paper have used 2 Q function networks. One of them is used to predict a high level policy, and the other is used to learn a low level policy. **Seohong Park, Dibya Ghosh, Benjamin Eysenbach, Sergey Levine. Arxiv 2024** 

2.[Reinforcement Learning for Versatile, Dynamic, and Robust Bipedal Locomotion Control](https://arxiv.org/pdf/2401.16889) This paper introduces a multi-stage method for bipedal locomotion control. The network inputs the short term history and the CNN feature of 2 second long history to output the policy. The method has 3 stages. First, it trains a single task by RL. Second, it trains tasks randomly to learn a general policy. Finally, it randomize the dynamics (the parameters of the environments and noise) to bridge the sim2real gap.  **Zhongyu Li, Xue Bin Peng, Pieter Abbeel, Sergey Levine, Glen Berseth, Koushil Sreenath. IJRR 2024** 


### Imitation Learning 



## Benchmark

## Datasets

## Industry
