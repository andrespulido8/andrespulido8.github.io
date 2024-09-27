---
layout: single
title: "Information Driven Guidance for Target Tracking with a Learned Motion Model"
permalink: /projects/info_driven_guidance_project/
author_profile: true
---

<video width="700" height="468" controls="controls">
  <source src="/videos/lcss_overview.mp4" type="video/mp4">
</video>

  

This paper presents a novel guidance law for target tracking applications where the target motion model is unknown and sensor measurements are intermittent due to unknown occlusions. In this work, the target motion model is represented by a transformer-based neural network and trained by previous target position measurements. This neural network (NN)-based motion model serves as the prediction step in a particle filter for target state estimation and uncertainty quantification. Then this estimation uncertainty is utilized in the information-driven guidance law to compute a path for the mobile agent to travel to a position with maximum expected entropy reduction (EER). The computation of EER is performed in real-time by approximating the probability distribution of the state using the particle representation from particle filter. Simulation and hardware experiments are performed with a quadcopter agent and TurtleBot target to demonstrate that the presented guidance law outperforms two other baseline guidance methods.
[[Poster]](/files/Pulido_MML_horizontal.pdf)[[Preprint]](https://arxiv.org/abs/2402.00671v1)(Waiting reviews in LCSS/ACC)

<img src="/images/FigFramework_annotated.png" width="550" /> 