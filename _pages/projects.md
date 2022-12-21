---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---
# (Under construction) 

## Research Projects

### Information Driven Guidance for Object Detection 
Project consisted of implementation of an information-driven trajectory planning for target tracking under noisy and intermittent measurements. The sensor planning algorithm  improves the target tracking performance by choosing the optimal sensor trajectory that allows sensors to obtain the most informative measurement, i.e., to minimize the uncertainty of the predicted distributtion made by a neural network.
(Work in progress)

<img src="/images/particles.png" width="450" /> 

### Trajectory Planning and Control of Bathy-drone: A Drone Towing a Boat equipped with Sonar for Bathymetry Mapping 
This paper considers a trajectory planning and control problem for a drone that drags an unpowered boat via a tether and is tasked with underwater bathymetry mapping. This platform, named Bathy-drone, consists of a boat equipped with a side-scan sonar sensor that can scan seafloor and obtain sonar imagery. Because the sonar vessel is unpowered, this platform is able to scan shallow water environment that other boats with propulsion system cannot navigate. However, because the sensing unit is dragged through a tether, which can be taut or loose, the vessel trajectory does not coincide with the drone trajectory. Additionally, obstacle avoidance must incorporate the delayed dynamics of the vessel because the drone can pull the vessel only when the tether is taut. This paper proposes a trajectory planning and control approach for a drone that can maneuver a tethered vessel such that the sensor field-of-view scans the entire given region of interest. The proposed trajectory planning and control approach will be developed by a Gazebo Simulator and demonstrated by experiments on a retention pond in Citra, FL.
(Work to be presented at SciTech Conference 2023)
<img src="/images/bathydrone_dynamics.png" width="450" /> 

### Time and Cost-Efficient Bathymetric Mapping System using Sparse Point Cloud Generation and Automatic Object Detection 
This paper introduces an efficient algorithm that generates a sparse 3D point cloud from side-scan sonar images. This computation is done in a computationally efficient manner by leveraging the geometry of the first sonar return combined with known positions provided by GPS and down-scan sonar depth measurement at each data point. Additionally, this paper implements another algorithm that uses YOLO, a Convolutional Neural Network (CNN) to perform object detection on side-scan sonar images collected in real life and generated with a simulation. The algorithm was tested on both real and synthetic images to show reasonably accurate anomaly detection and classification.
[[Code]](https://github.com/andrespulido8/jupyter-notebooks/tree/aaa897c4248bb9b09f7f74eba1f3798313333720) [[Presentation]](/files/OCEANS-1.pdf) [[Preprint]](https://arxiv.org/abs/2210.10263)

<img src="/images/oceans.png" width="450" /> 
<img src="/images/object_detection.png" width="450" /> 

## Course Projects

### Optimal Control Theory for Trajectory Generation of an Orbital Spacecraft
Optimal control theory was used to solve a trajectory generation of an orbital spacecraft and a minimum time transfer of a ground mobile between a given initial and terminal state problems. Indirect and direct with single and multiple shooting methods were implemented from scratch in Python. 
[[Code]](https://github.com/andrespulido8/optimal_control_examples)

<img src="/images/polar_traj.png" width="450" /> 

## Competition Projects

### System ID, dynamic modeling, and control of a 6-DOF underwater vehicle: SubjuGator 
 The model of a submarine contains unknown parameters that needed to be found in either simulations or experimentation with the physical vehicle. In this undergrad thesis I  performed two methods that find the uncertain parameters. The location of the COM differed between the Solidworks model and the one found in experiments by a maximum of 12.5% change. The linear and quadratic parameters found in the surge, sway, and yaw static experiments are similar to the ones found by other researchers with other AUVs.
[[Website]](https://sites.google.com/) [[Code]](https://github.com/)

<img src="/images/subjugator.png" width="450" /> 

