---
title: "Information Driven Guidance for Target Tracking with a Learned Motion Model"
permalink: /projects/info_driven_guidance_project/
author_profile: true
---

## Uncertainty-Aware Guidance for Target Tracking subject to Intermittent Measurements using Motion Model Learning 
**Andres Pulido**, Kyle Volle, Kristy Waters, Zachary I. Bell, Prashant Ganesh and Jane Shin

This paper presents a novel guidance law for target tracking applications where the target motion model is unknown and sensor measurements are intermittent due to unknown occlusions. In this work, the target motion model is represented by a transformer-based neural network and trained by previous target position measurements. This neural network (NN)-based motion model serves as the prediction step in a particle filter for target state estimation and uncertainty quantification. Then this estimation uncertainty is utilized in the information-driven guidance law to compute a path for the mobile agent to travel to a position with maximum expected entropy reduction (EER). The computation of EER is performed in real-time by approximating the probability distribution of the state using the particle representation from particle filter. Simulation and hardware experiments are performed with a quadcopter agent and TurtleBot target to demonstrate that the presented guidance law outperforms two other baseline guidance methods.
[[Poster]](/files/Pulido_MML_horizontal.pdf) [[Preprint]](https://arxiv.org/abs/2402.00671v1) [[ACC 2025 Conference paper]](https://ieeexplore.ieee.org/document/11107429)

<video width="700" height="468" controls="controls">
  <source src="/videos/lcss_overview.mp4" type="video/mp4">
</video>

## Transformer-based Motion Model for Robust Target Tracking under Intermittent and Noisy Measurements 
**Andres Pulido**, Kyle Volle, Zachary I. Bell and Jane Shin

Target tracking under intermittent measurements is a fundamental challenge in autonomous systems. Traditional methods, including Kalman filters and deep learning-based models, often struggle with sparse observations that contain large noise. In this paper, we formulate multiple transformer-based motion model designs that learn target dynamics from noisy sensor measurements and occluded portions. The models leverage self-attention to capture temporal dependencies and infer motion patterns under uncertainty. We evaluate different motion model formulations, such as time encoding the position inputs to handle the occlusion. These motion models are then paired with a particle filter for target estimation and with an information-driven planner for agent's guidance law. Since the motion models feed the prediction outputs into the guidance, their effectiveness is evaluated considering the target tracking performance. Simulation and hardware experiments demonstrate improved tracking accuracy and robustness compared to existing approaches.
(Accepted to IROS 2025)

<img src="/images/data_architectures.png" width="550" /> 

<img src="/images/true_noisy_comp.png" width="370" /> 
<img src="/images/veltra_train.png" width="390" /> 
<img src="/images/veltra_predictions.png" width="390" /> 