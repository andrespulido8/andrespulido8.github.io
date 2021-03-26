---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---
## Current projects
### Improving Human-Robot Collaboration through Active Intent Estimation
Collaborators: Haonan Chen, Peixin Chang, Prof. Katie Driggs-Campbell

### Wayfinding Assistance Robot for People with Visual Impairments
Collaborators: Aamir Hassan, Megan Bayles, Eric Liang, Prof. Katie Driggs-Campbell, Prof. Wendy Rogers, and many others

### Developing Robot Sensorimotor Contigency by Self-supervised Learning: Combining Sight and Sound in Learning-Based Control
Collaborators: Peixin Chang, Prof. Katie Driggs-Campbell

### Hierarchical Self-Imitation Learning for Single-Agent Tasks with Sparse Rewards
Collaborators: Neeloy Chakraborty, Prof. Katie Driggs-Campbell

## Past projects

### Decentralized Structural-RNN for Robot Crowd Navigation with Deep Reinforcement Learning
Safe and efficient navigation through human crowds is an essential capability for mobile robots. 
Previous work on robot crowd navigation assumes that the dynamics of all agents are known and well-defined. 
In addition, the performance of previous methods deteriorates in partially observable environments and environments with dense crowds. 
To tackle these problems, we propose decentralized structural-Recurrent Neural Network (DS-RNN), a novel network that reasons about spatial and temporal relationships for robot decision making in crowd navigation. 
We train our network with model-free deep reinforcement learning without any expert supervision. 
We demonstrate that our model outperforms previous methods and successfully transfer the policy learned in the simulator to a real-world TurtleBot 2i.  
[[Paper]](https://arxiv.org/abs/2011.04820) [[Code]](https://github.com/Shuijing725/CrowdNav_DSRNN) [[Video]](https://www.youtube.com/watch?v=AYugucvez4Q)  
<img src="/images/crowdnav.jpg" width="450" />   

### [Robot Sound Interpretation: Combining Sight and Sound in Learning-Based Control](https://sites.google.com/site/changpeixin/home/Research/robot_sound_interpretation)
We explore the interpretation of sound for robot decision-making, inspired by human speech comprehension.
While previous methods use natural language processing to translate sound to text, we propose an end-to-end
deep neural network which directly learns control polices from images and sound signals.  
[[Paper]](https://arxiv.org/abs/1909.09172) [[Video]](https://www.youtube.com/watch?v=0ONGQwhGn_Y)  
<img src="/images/rsi_opening.png" width="800" />

### Robust Deep Reinforcement Learning with Adversarial Attacks
We propose adversarial attacks for Reinforcement Learning (RL) algorithms and then improves the robustness of these algorithms 
with adversarial training using these attacks. We found that this adversarial training of deep RL algorithms like Double-DQN 
and DDPG leads to significant increase in robustness to parameter variations in OpenAI Gym benchmarks.  
[[Paper]](https://arxiv.org/abs/1712.03632) [[Video]](https://www.youtube.com/watch?v=8xPaca3cjEU) [[Poster]](/files/daslab_poster.pdf) [[Supplementary materials]](https://shuijing725.github.io/files/Supplementary_for_Robust_Deep_Reinforcement_Learning_with_Adversarial_Attacks.pdf)

### Prostate Cancer Diagnosis by Deep Learning
Nowsdays prostate cancer diagnosis by biopsy images requires expensive equipments and experienced trained pathologists.
With recent advances in computer vision and machine intelligence, we tackle this problem by classifying biopsy images into 
positive or negative classes using a state-of-art convolutional neural network called ResNet. We achieved around 82% accuracy 
on some datasets and further boosted the accuracy to nearly 100% by ensemble methods.  
[[Abstract]](https://www.ideals.illinois.edu/handle/2142/100023) [[Paper]](/files/ECE499-Sp2018-liu-Shuijing.pdf) [[Slides]](/files/senior_thesis_presentation.pdf)
<div class="imageContainer">
<img src="/images/cancer_diagnosis.png" width="1100" />
</div>
