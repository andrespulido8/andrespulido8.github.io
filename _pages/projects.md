---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---
## Current projects

### Decentralized Vision-based Robot Crowd Navigation
State-of-art decentralized robot crowd navigation algorithms have assumed full state observability of all agents in the environment. 
But the sensor measurement of full state information can be expensive and sometimes inaccessible. To achieve safe and low-cost robot crowd
navigation, we reformulate this problem by replacing the sensors with only one RGBD camera, 
thus removing the full observability assumption.
For now, we find the performance of state-of-art algorithms degrade significantly if the robot only has a limited field-of-view. 
<img src="/images/CrowdMove.png" width="800" />   

(Photo credit https://gamma.umd.edu)
## Past projects

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