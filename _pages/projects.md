---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---
## Current projects

### Socially Aware Robot Crowd Navigation with Interaction Graphs and Human Trajectory Prediction  
We study the problem of safe and socially aware robot navigation in dense and interactive human crowds.
In this paper, we provide a more accurate representation of personal zones of walking pedestrians with their future trajectories. 
The predicted personal zones are incorporated into a reinforcement learning framework to prevent the robot from intruding into the personal zones. 
To learn socially aware navigation policies, we propose a novel recurrent graph neural network with attention mechanisms to capture the interactions among agents through space and time. 
We demonstrate that our method enables the robot to achieve good navigation performance and non-invasiveness in challenging crowd navigation scenarios.   
[[Paper]](https://arxiv.org/abs/2203.01821) [[Video]]()

<img src="/images/socialZone.png" width="450" /> 

### Wayfinding Assistance Robot for People with Visual Impairments  
Recent studies find that independent navigation is especially difficult for people with visual impairments.
The currently available tools for wayfinding are fairly limited to white canes, guide dogs, etc.
Providing a robot guide that could facilitate wayfinding in a variety of environments would significantly improve the quality of life and, 
most importantly, the independence of people with vision impairments. 
Through this project, we will explore the feasibility of robot navigation for guidance and wayfinding.    

<img src="/images/wayfinding.jpg" width="450" />    
(Photo credit: Travis Kadylak)

### World in Motion: Geometry-based Video Prediction with Visual Odometry Prediction and View Synthesis   
Video prediction has a wide range of applications in planning and control for robotics. 
However, previous do not account for camera motion and perform poorly in scenarios with moving cameras when they are deployed on autonomous vehicles and mobile robots. 
We propose a geometry-based prediction framework named World in Motion. 
Based on a sequence of observed frames, our method first predicts future camera poses and extracts the 3D geometry of the world, which are then jointly used to generate predicted future frames. 
Specifically, we train a recurrent visual odometry model conditioned on raw RGB images with ground truth pose labels.
Then, we train SynSin, a view synthesis method to generate 2D images from novel viewpoints using a 3D world representation. 
We demonstrate that our hierarchical deterministic approach outperforms previous stochastic works on the KITTI dataset.  

<img src="/images/world_in_motion.jpg" width="800" />

## Past projects

### Learning to Navigate Intersections with Unsupervised Driver Trait Inference
Navigation through uncontrolled intersections is one of the key challenges for autonomous vehicles.
Identifying the subtle differences in hidden traits of other drivers can bring significant benefits when navigating in such environments.
We propose an unsupervised method for inferring driver traits such as driving styles from observed vehicle trajectories. 
Then, we use the inferred traits to improve the navigation of an autonomous vehicle through a T-intersection. 
Our pipeline enables the autonomous vehicle to adjust its actions when dealing with drivers of different traits to ensure safety and efficiency.   
[[Paper]](https://arxiv.org/abs/2109.06783) [[Website]](https://sites.google.com/illinois.edu/vae-trait-inference/home) [[Code]](https://github.com/Shuijing725/VAE_trait_inference) [[Video]](https://www.youtube.com/watch?v=wqbgsjSvkAo&t=1s)            

<img src="/images/trait_opening.png" width="450" /> 

### Robot Sound Interpretation: Learning Visual-Audio Representations for Voice-Controlled Robots
Inspired by sensorimotor theory, we propose a novel pipeline for voice-controlled robots. 
We learn a representation that associates images and sound commands with minimal supervision. 
Using this representation, we generate an intrinsic reward function to learn robotic tasks with reinforcement learning. 
We demonstrate our approach on three robot platforms, a TurtleBot3, a Kuka-IIWA arm, and a Kinova Gen3 robot, which hear a command word, identify the associated target object, and perform precise control to approach the target. 
We successfully deploy the policy learned in simulator to a real-world Kinova Gen3.   
[[Paper]](https://arxiv.org/abs/2109.02823)    

<img src="/images/rsi2_opening.png" width="800" />  

### Decentralized Structural-RNN for Robot Crowd Navigation with Deep Reinforcement Learning
Safe and efficient navigation through human crowds is an essential capability for mobile robots. 
We propose decentralized structural-Recurrent Neural Network (DS-RNN), a novel network that reasons about spatial and temporal relationships for robot decision making in crowd navigation. 
We train our network with model-free deep reinforcement learning without any expert supervision. 
We demonstrate that our model outperforms previous methods and successfully transfer the policy learned in the simulator to a real-world TurtleBot 2i.  
[[Paper]](https://arxiv.org/abs/2011.04820) [[Website]](https://sites.google.com/illinois.edu/crowdnav-dsrnn/home) [[Code]](https://github.com/Shuijing725/CrowdNav_DSRNN) [[Video]](https://youtu.be/bYO-1IAjzgY)  

<img src="/images/crowdnav.jpg" width="450" />   

### Robot Sound Interpretation: Combining Sight and Sound in Learning-Based Control
We explore the interpretation of sound for robot decision-making, inspired by human speech comprehension.
While previous methods use natural language processing to translate sound to text, we propose an end-to-end
deep neural network which directly learns control polices from images and sound signals.  
[[Paper]](https://arxiv.org/abs/1909.09172) [[Website]](https://sites.google.com/site/changpeixin/home/Research/robot_sound_interpretation) [[Video]](https://www.youtube.com/watch?v=0ONGQwhGn_Y)  

<img src="/images/rsi_opening.png" width="800" />

### Occlusion-Aware Crowd Navigation Using People as Sensors   
Occlusions are highly prevalent in crowded spaces due to a limited robot sensor range and obstructing human agents. 
We propose integrating such social inference techniques into the planning pipeline.
We use a variational autoencoder with a specially designed loss function to learn representations that are meaningful for occlusion inference. 
We develop a deep reinforcement learning algorithm that incorporates the learned representations for occlusion-aware path planning that simultaneously learns to avoid collision with both observed and occluded human agents.
We demonstrate that our occlusion-aware policy can estimate agents in occluded spaces and achieves comparable navigation performance to a navigation policy with omniscient, full map information. 
To the best of our knowledge, this work is the first to use social occlusion inference for crowd navigation.
<img src="/images/pas.png" width="300" />

### Off Environment Evaluation Using Convex Risk Minimization   
Applying reinforcement learning (RL) methods on robots typically involves training a policy in simulation and deploying it on a robot in the real world. 
However, model mismatch between the real world and the simulator causes RL agents to perform suboptimally.
To address this, we propose a convex risk minimization algorithm to estimate the model mismatch between the simulator and the target domain. 
We show that this estimator can be used to evaluate performance of RL agents in the target domain, effectively bridging the gap between simulation and real world. 
Our experiments demonstrate that our method effectively evaluates performance of policies in OpenAI Gym environments and a real Kinova Gen3 arm.  
[[Paper]](https://arxiv.org/abs/2112.11532) [[Code]](https://github.com/pulkitkatdare/offenveval)

### Hierarchical Self-Imitation Learning for Single-Agent Tasks with Sparse Rewards
Reinforcement learning problems with sparse and delayed rewards are challenging to solve.
We propose a single agent reinforcement learning algorithm named HAC+GASIL that combines Generative Adversarial Self-Imitation Learning (GASIL) and
Hierarchical Actor-Critic (HL).
HAC+GASIL divides the policy of an agent into multiple levels and the hierarchical policy can be trained end-to-end.
To evaluate HAC+GASIL, we perform experiments in OpenAI Multi-Agent Particle Environment with sparse and delayed reward stochastic scenarios.   
[[Paper]](https://www.ideals.illinois.edu/handle/2142/110267)

### Robust Deep Reinforcement Learning with Adversarial Attacks
We propose adversarial attacks to perturb reinforcement learning algorithms (e.g. DQN, DDPG, etc), and then uses adversarial training to improve the robustness of these algorithms.
We found that our adversarial training significantly improves the robustness of RL algorithms to parameter variations in OpenAI Gym benchmarks.  
[[Paper]](https://arxiv.org/abs/1712.03632) [[Video]](https://www.youtube.com/watch?v=8xPaca3cjEU) [[Poster]](/files/daslab_poster.pdf) [[Supplementary materials]](https://shuijing725.github.io/files/Supplementary_for_Robust_Deep_Reinforcement_Learning_with_Adversarial_Attacks.pdf)

### Prostate Cancer Diagnosis by Deep Learning
Prostate cancer diagnosis requires expensive equipments and experienced trained pathologists.
With recent advances in computer vision, we classify cancerous and healthy tissue biopsy images using ResNet. 
Then, we use ensemble methods to boost the performance of ResNet models and achieve nearly perfect testing performance on the US Biomax prostate cancer dataset.   
[[Abstract]](https://www.ideals.illinois.edu/handle/2142/100023) [[Paper]](/files/ECE499-Sp2018-liu-Shuijing.pdf) [[Slides]](/files/senior_thesis_presentation.pdf)

<div class="imageContainer">
<img src="/images/cancer_diagnosis.png" width="1100" />
</div>
