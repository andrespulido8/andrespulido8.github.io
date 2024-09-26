---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---
## Research Projects

### Information Driven Guidance for Target Tracking with a Learned Motion Model 

<img src="/images/FigFramework_annotated.png" width="450" /> 

Project consisted of implementation of an information-driven trajectory planning for target tracking under noisy and intermittent measurements. The sensor planning algorithm improves the target tracking performance by choosing the optimal sensor trajectory that allows sensors to obtain the most informative measurement, i.e., to minimize the uncertainty of the predicted distribution made by a transformer-based neural network. I worked on the problem formulation, solution derivation and hardware implementation to evaluate the algorithm with other baselines.
[[Poster]](/files/Pulido_MML_horizontal.pdf)(Reviewing for submission to RA-L)

<video width="480" height="320" controls="controls">
  <source src="/videos/overhead_particles_3X.mp4" type="video/mp4">
</video>

### Trajectory Planning and Control of Bathy-drone: A Drone Towing a Boat equipped with Sonar for Bathymetry Mapping 
<img src="/images/bathydrone.gif" width="450" /> 

This paper considers a trajectory planning and control problem for a drone that drags an unpowered boat via a tether and is tasked with underwater bathymetry mapping. This platform, named Bathy-drone, consists of a boat equipped with a side-scan sonar sensor that can scan the seafloor and obtain sonar imagery. Because the sonar vessel is unpowered, this platform is able to scan shallow water environments that other boats with propulsion systems cannot navigate. However, because the sensing unit is dragged through a tether, which can be taut or loose, the vessel trajectory does not coincide with the drone trajectory. Additionally, obstacle avoidance must incorporate the delayed dynamics of the vessel because the drone can pull the vessel only when the tether is taut. This paper proposes a trajectory planning and control approach for a drone that can maneuver a tethered vessel such that the sensor field-of-view scans the entire given region of interest. The proposed trajectory planning and control approach will be developed by a Gazebo Simulator and demonstrated by experiments on a retention pond in Citra, FL.
[[Conference paper]](https://arc.aiaa.org/doi/10.2514/6.2023-1811), [[Presentation]](/files/Pulido_SciTech23.pdf)
<img src="/images/bathydrone_annotated.png" width="450" /> 
<img src="/images/bathydrone_dynamics.png" width="450" /> 

### Time and Cost-Efficient Bathymetric Mapping System using Sparse Point Cloud Generation and Automatic Object Detection 
This paper introduces an efficient algorithm that generates a sparse 3D point cloud from side-scan sonar images. This computation is done in a computationally efficient manner by leveraging the geometry of the first sonar return combined with known positions provided by GPS and down-scan sonar depth measurement at each data point. Additionally, this paper implements another algorithm that uses YOLO, a Convolutional Neural Network (CNN) to perform object detection on side-scan sonar images collected in real life and generated with a simulation. The algorithm was tested on both real and synthetic images to show reasonably accurate anomaly detection and classification.
[[Code]](https://github.com/andrespulido8/jupyter-notebooks/tree/aaa897c4248bb9b09f7f74eba1f3798313333720), [[Presentation]](/files/OCEANS-1.pdf), [[Preprint]](https://arxiv.org/abs/2210.10263), [[Conference Paper]](https://ieeexplore-ieee-org.lp.hscl.ufl.edu/document/9977073)

<img src="/images/oceans.png" width="450" /> 
<img src="/images/object_detection.png" width="450" /> 

## Competition Projects

### System ID, dynamic modeling, control, and state estimation of a underwater vehicle - SubjuGator and a autonomous sruface vehicle - NaviGator  
As part of the Machine Intelligence Lab (MIL) at the University of Florida, since 2018, I served as the lead mechanical engineer, a software team member and I am now adivising the team. A small sample of the projects I have led are: [[Website]](http://subjugator.org/), [[Code]](https://github.com/uf-mil/mil/)
- I have been currently writing an unscented Kalman filter to do state estimation for the next-generation submarine. 
- To take into account external disturbances, I have also implemented a Concurrent Learning-based adaptive controller for the surface vehicle boat that learns systems parameters.  
- The model of a submarine contains unknown parameters that needed to be found in either simulations or experimentation with the physical vehicle. Therfore, I performed a system ID method by fitting data collected in the pool to a dynamic model and find the drag and inertia parameters of the submarine.


<img src="/images/subjugator.png" width="400" /> 
<img src="/images/NaviGator.png" width="450" /> 

## Course Projects

I have taken several courses that have allowed me to work on interesting projects. Some of are Nonlinear Programming, Optimal Control, and Reinfocement Learning, Adaptive Control, Neural Networks and Machine Learning, and more. The following is an example a course project I have worked on: 
### Optimal Control Theory for Trajectory Generation of an Orbital Spacecraft
Optimal control theory was used to solve a trajectory generation of an orbital spacecraft and a minimum time transfer of a ground mobile between a given initial and terminal state problems. Indirect and direct with single and multiple shooting methods were implemented from scratch in Python. 
[[Code]](https://github.com/andrespulido8/optimal_control_examples)

<img src="/images/polar_traj.png" width="450" /> 
