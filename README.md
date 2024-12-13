# Awesome_AI_for_Robotics
As ChatGPT and RT2 appears, many researchers start to do reseaches about AI for robotics. Many scholars have different names for it, including embodied AI, smart robotics, etc. I don't care what its name really is, I just want to share what I have learnt. Hope it helps!

## Main Challenges
1. Accuracy (Including RL, IL, network structure)
2. Generality
3. Inference speed
4. Datasets
5. Sim2Real

## Tutorials & Slides
1. [Deep Reinforcement Learning slides by Sergey Levine CS 285 at UC Berkeley](https://rail.eecs.berkeley.edu/deeprlcourse/)
A very good slide to learn the basic concepts of reinforcement learning. Super clear. **Institution： UC Berkeley**



## Papers

### Reinforcement Learning
1.[HIQL: Offline Goal-Conditioned RL
with Latent States as Actions](https://proceedings.neurips.cc/paper_files/paper/2023/file/6d7c4a0727e089ed6cdd3151cbe8d8ba-Paper-Conference.pdf)
This paper introduces a new way to improve the performance of action-free offline reinforcement learning. Most of the time, when we want to do training in action-free offline reinforcement learning, we need to train a value network and use it to update a Q function network. However, the authors in this paper have used 2 Q function networks. One of them is used to predict a high level policy, and the other is used to learn a low level policy. **Seohong Park, Dibya Ghosh, Benjamin Eysenbach, Sergey Levine. Arxiv 2024** 
![image](https://github.com/user-attachments/assets/0f2547b4-4fbb-43a3-9f15-ff863d0e3a05)


2.[Reinforcement Learning for Versatile, Dynamic, and Robust Bipedal Locomotion Control](https://arxiv.org/pdf/2401.16889) This paper introduces a multi-stage method for bipedal locomotion control. The network inputs the short term history and the CNN feature of 2 second long history to output the policy. The method has 3 stages. First, it trains a single task by RL. Second, it trains tasks randomly to learn a general policy. Finally, it randomize the dynamics (the parameters of the environments and noise) to bridge the sim2real gap.  **Zhongyu Li, Xue Bin Peng, Pieter Abbeel, Sergey Levine, Glen Berseth, Koushil Sreenath. IJRR 2024** 

3.[Steering Your Generalists: Improving Robotic Foundation Models via Value Guidance](https://openreview.net/pdf?id=6FGlpzC9Po)
This paper learns a value action conditioned on the language guide based on lanrge dataset training. When in reference, we can use the value function the sample the best action in multiple choices. The formula below is how to train the value function Q. **Mitsuhiko Nakamoto, Oier Mees, Aviral Kumar, Sergey Levine. CoRL 2024** 
![image](https://github.com/user-attachments/assets/62870f16-21aa-4909-a35e-d07bad3695b7)



### Imitation Learning 





## Industry
Here we update some tech advance in the industry🔥🔥🔥
There are too many start-ups doing the same thing, boring and useless. So, we will only update the AI for robotic start-ups who make **innovative products**

1.[Clone AI](https://www.clonerobotics.com/)
Cloning human beings' body structure to make a humanoid robot.
![image](https://github.com/user-attachments/assets/3a750590-e473-4ce3-a60e-d55d30996af6)

2.[Tesla Optimus](https://x.com/Tesla_Optimus)
The renown Tesla robotics. AGI for robotic control. 
![image](https://github.com/user-attachments/assets/82d682bc-9229-4b94-affd-6a028fbcd162)

3.[Physical Intelligence](https://www.physicalintelligence.company/)
An algorithm company. Designing AI algorithms for robotics. Its founders include lots of renown scholars in robotic area.
![image](https://github.com/user-attachments/assets/99f16bfa-4382-4609-a835-1406d5b7f565)




