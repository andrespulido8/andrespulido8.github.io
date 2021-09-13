---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: false
---
## Current projects

### Wayfinding Assistance Robot for People with Visual Impairments
Collaborators: Aamir Hassan, Kaiwen Hong, Megan Bayles, Eric Liang, Prof. Katie Driggs-Campbell, Prof. Wendy Rogers, and many others

To navigate independently in a physical environment, people generally rely on visual cues to understand the environment.
However, recent studies find that this is especially difficult for people with visual impairments.
The currently available tools and technology for wayfinding are fairly limited to white canes, guide dogs, etc.
Providing a robot guide that could facilitate wayfinding in a variety of environments would significantly improve the quality of life and, 
most importantly, the independence of people with vision impairments. Through this project, we will explore the feasibility of robot navigation for guidance and wayfinding.    
<img src="/images/wayfinding.jpg" width="450" />    
(Photo credit: Travis Kadylak)

### Robot Crowd Navigation with Pedestrian Trajectory Prediction and Self-Attention DS-RNN
Collaborators: Peixin Chang, Zhe Huang, Junyi(Jenny) Geng, Prof. Katie Driggs-Campbell

We continue to explore robot crowd navigation with deep reinforcement learning.
To increase the social awareness of the robot behaviors, we incorporate the predicted future trajectories of surrounding pedestrians into robot decision-making.
To improve our previous Decentralized Structural-RNN (DS-RNN) network, we use a self-attention module to deal with a changing number of humans 
and removes the requirement for human ID tracking.



## Past projects

### Learning to Navigate Intersections with Unsupervised Driver Trait Inference
Navigation through uncontrolled intersections is one of the key challenges for autonomous vehicles.
Identifying the subtle differences in hidden traits of other drivers can bring significant benefits when navigating in such environments.
We propose an unsupervised method for inferring driver traits such as driving styles from observed vehicle trajectories. 
We use a variational autoencoder with recurrent neural networks to learn a latent representation of traits without any ground truth trait labels.
Then, we use this trait representation to learn a policy for an autonomous vehicle to navigate through a T-intersection with deep reinforcement learning. 
Our pipeline enables the autonomous vehicle to adjust its actions when dealing with drivers of different traits to ensure safety and efficiency. 
Our method demonstrates promising performance and outperforms state-of-the-art baselines in the T-intersection scenario.
[[Paper]]()
<img src="/images/trait_opening.png" width="450" /> 

### Robot Sound Interpretation: Learning Visual-Audio Representations for Voice-Controlled Robots
Inspired by sensorimotor theory, we propose a novel pipeline for voice-controlled robots. 
Previous work relies on explicit labels of sounds and images as well as extrinsic reward functions. 
Not only do such approaches have little resemblance to human sensorimotor development, but also require hand-tuning rewards and extensive human labor. 
To address these problems, we learn a representation that associates images and sound commands with minimal supervision. 
Using this representation, we generate an intrinsic reward function to learn robotic tasks with reinforcement learning. 
We demonstrate our approach on three robot platforms, a TurtleBot3, a Kuka-IIWA arm, and a Kinova Gen3 robot, which hear a command word, identify the associated target object, and perform precise control to approach the target. 
We show that our method outperforms previous work across various sound types and robotic tasks empirically. 
We successfully deploy the policy learned in simulator to a real-world Kinova Gen3.
[[Paper]](https://arxiv.org/abs/2109.02823) 
<img src="/images/rsi2_opening.png" width="800" />  

### Decentralized Structural-RNN for Robot Crowd Navigation with Deep Reinforcement Learning
Safe and efficient navigation through human crowds is an essential capability for mobile robots. 
Previous work on robot crowd navigation assumes that the dynamics of all agents are known and well-defined. 
In addition, the performance of previous methods deteriorates in partially observable environments and environments with dense crowds. 
To tackle these problems, we propose decentralized structural-Recurrent Neural Network (DS-RNN), a novel network that reasons about spatial and temporal relationships for robot decision making in crowd navigation. 
We train our network with model-free deep reinforcement learning without any expert supervision. 
We demonstrate that our model outperforms previous methods and successfully transfer the policy learned in the simulator to a real-world TurtleBot 2i.  
[[Paper]](https://arxiv.org/abs/2011.04820) [[Website]](https://sites.google.com/illinois.edu/crowdnav-dsrnn/home) [[Code]](https://github.com/Shuijing725/CrowdNav_DSRNN) [[Video]](https://youtu.be/bYO-1IAjzgY)  
<img src="/images/crowdnav.jpg" width="450" />   

### [Robot Sound Interpretation: Combining Sight and Sound in Learning-Based Control](https://sites.google.com/site/changpeixin/home/Research/robot_sound_interpretation)
We explore the interpretation of sound for robot decision-making, inspired by human speech comprehension.
While previous methods use natural language processing to translate sound to text, we propose an end-to-end
deep neural network which directly learns control polices from images and sound signals.  
[[Paper]](https://arxiv.org/abs/1909.09172) [[Website]](https://sites.google.com/site/changpeixin/home/Research/robot_sound_interpretation) [[Video]](https://www.youtube.com/watch?v=0ONGQwhGn_Y)  
<img src="/images/rsi_opening.png" width="800" />

### Hierarchical Self-Imitation Learning for Single-Agent Tasks with Sparse Rewards
Reinforcement learning problems with sparse and delayed rewards are challenging to solve because the algorithms explore environments to gain experience from high performing rollouts.
Classical methods of encouraging exploration during training such as ε-greedy and noise-based exploration are not adequate on their own to explore large state spaces.
We propose a single agent reinforcement learning algorithm named HAC+GASIL that combines Generative Adversarial Self-Imitation Learning (GASIL) and
Hierarchical Actor-Critic (HL).
HAC+GASIL represents the agent as multiple trainable levels of Deep Deterministic Policy Gradient (DDPG) optimizers, 
where the purpose of the higher-level policies is to set waypoints to guide the lower levels policies to receive the highest cumulative return. 
To evaluate HAC+GASIL, we perform experiments in OpenAI Multi-Agent Particle Environment with sparse and delayed reward stochastic scenarios.
[[Paper]](https://www.ideals.illinois.edu/handle/2142/110267)

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
