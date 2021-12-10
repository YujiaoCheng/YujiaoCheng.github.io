---
layout: archive
title: ""
permalink: /research/
author_profile: true
---

<p align="center">
<img src="/images/robotSystem.png" width="500">
</p>


## Human Plan Recognition via Hierarchical Modeling \[[pdf](https://ieeexplore.ieee.org/abstract/document/8990024)\] \[[video](https://www.youtube.com/watch?v=4DlgnFjfwkY)\] 
<p align="center">
<img src="/images/plan.png" width="700">
</p>
 To efficiently finish tasks in human-robot collaboration systems, the robots need to recognize human's intentions for a plan, i.e., the sequence of actions to finish the tasks. However, due to the stochastic and time-varying nature of human collaborators, it is quite challenging for the robot to efficiently and accurately identify such task plans. To address this challenge, we propose a hirarchical modeling method by explicitly leveraging the hierarchical relationship between plans and trajectories, which is data-efficient and intepretable. Physical experiments were conducted on an industrial robot to verify the proposed framework. The results show that the proposed framework could accurately recognize the human workers' plans and thus significantly improve the time efficiency of the human-robot collaboration.

## Short-Term Human Trajectory Prediction Using Semi-adaptable Neural Network \[[pdf](https://ieeexplore.ieee.org/abstract/document/8814980)\]\[[video](https://www.youtube.com/watch?v=2dqS9r0xBGo)\]
<p align="center">
<img src="/images/adaptable_NN.jpg" width="600">
</p>
Human motion prediction is an important component to facilitate human robot interaction. Robots need to accurately predict human's future movement in order to safely plan its own motion trajectories and efficiently collaborate with humans. Many recent approaches predict human's movement using deep learning methods, such as recurrent neural networks. However, existing methods lack the ability to adapt to time-varying human behaviors, and many of them do not quantify uncertainties in the prediction. This paper proposes an approach that uses a semi-adaptable neural network for human motion prediction, and provides uncertainty bounds of the predictions in real time. In particular, a neural network is trained offline to represent the human motion transition model, and then recursive least square parameter adaptation algorithm (RLS-PAA) is adopted for online parameter adaptation of the neural network and for uncertainty estimation. Experiments on several human motion datasets verify that the proposed method significantly outperforms the state-of-the-art approach in terms of prediction accuracy and computation efficiency.

## Long-Term Human Trajectory Prediction Using Adaptable Sigma Lognormal Functions \[[pdf](https://ieeexplore.ieee.org/abstract/document/9599389)\]
<p align="center">
<img src="/images/lognormal.png" width="500">
</p>

In the framework of human-robot collaborative assembly, it is important to predict the long-term human hand trajectory for collision avoidance and to estimate the durations of the human actions for collaborative task planning. Many existing works predict long-term human trajectory by a preset time horizon, while in this paper, our prediction horizon depends on how far in the future we could predict the human's actions. To be more specific, we predict the human trajectory and estimate the durations for the human's current action and future actions. We propose to use the sigma-lognormal function to model and predict the human movement, and from this model we estimate the action durations. To accommodate different human behaviors, we also propose an online algorithm to adapt the movement model by using the observed trajectory, the human intentions and the scene layout.
The effectiveness of the proposed framework is supported by experimental validations on the human trajectory data for conducting a computer assembly task. 

## Human-Aware Task Planning \[[pdf](https://ieeexplore.ieee.org/abstract/document/9345470)\]\[[video](https://www.youtube.com/watch?v=wfle8Ry7z54)\]
<p align="center">
<img src="/images/taskPlanning.png" width="300">
</p>
When robots work with humans for collaborative task, they need to plan their actions while taking humans' actions into account. However, due to the complexity of the tasks and stochastic nature of human collaborators, it is quite challenging for the robot to efficiently collaborate with the humans. To address this challenge, in this letter, we first propose an algorithm to automatically construct a hierarchical task model from single-agent demonstrations. The hierarchical task model explicitly captures the sequential and parallel relationships of the task at all levels of abstraction. We then propose an optimization-based planner, which exploits the parallel relationships and prioritizes actions that are parallel to the humans' actions. In such a way, potential spatial interfaces can be avoided, task completion time can be reduced, and human's satisfaction level can be improved. We conducted simulations of a robot arm collaborating with a human for several collaborative tasks. The comparison results with several baselines proved that our proposed planner is better in terms of efficiency, safety and human satisfaction.
