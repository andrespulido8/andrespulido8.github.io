---
layout: single
title: "Bathydrone: Autonomous Drone and Boat-Tethered Robot"
permalink: /projects/bathydrone_project/
author_profile: true
---

<video width="700" height="462" controls="controls">
  <source src="/videos/Bathy_promotion.mp4" type="video/mp4">
</video>

## Trajectory Planning and Control of Bathy-drone: A Drone Towing a Boat equipped with Sonar for Bathymetry Mapping
**Andres Pulido**, Antonio Diaz, Andrew Ortega, Peter Ifju, Jane Shin.  
This paper considers a trajectory planning and control problem for a drone that drags an unpowered boat via a tether and is tasked with underwater bathymetry mapping. This platform, named Bathy-drone, consists of a boat equipped with a side-scan sonar sensor that can scan the seafloor and obtain sonar imagery. Because the sonar vessel is unpowered, this platform is able to scan shallow water environments that other boats with propulsion systems cannot navigate. However, because the sensing unit is dragged through a tether, which can be taut or loose, the vessel trajectory does not coincide with the drone trajectory. Additionally, obstacle avoidance must incorporate the delayed dynamics of the vessel because the drone can pull the vessel only when the tether is taut. This paper proposes a trajectory planning and control approach for a drone that can maneuver a tethered vessel such that the sensor field-of-view scans the entire given region of interest. The proposed trajectory planning and control approach will be developed by a Gazebo Simulator and demonstrated by experiments on a retention pond in Citra, FL.  
[[Conference paper]](https://arc.aiaa.org/doi/10.2514/6.2023-1811), [[Presentation]](/files/Pulido_SciTech23.pdf)

<img src="/images/bathydrone_dynamics.png" width="425" /> 
<img src="/images/gazebo_sim2.png" width="330" /> 

## Coverage path planning for a robotics platform equipped with a side-scan sonar sensor for underwater bathymetry mapping
**Andres Pulido**, Blake Sanders, Nicholas Sardinia, Antonio Diaz, Henry Tingle, Peter Ifju and Jane Shin.  
This paper introduces a Coverage Path Planning (CPP) algorithm for underwater bathymetry mapping of small water bodies. The presented CPP algorithm is designed to be adaptable to various geometries and scales of target regions and sensor field-of-views (FOVs), making it particularly suitable for non-holonomic vehicles like the Bathy-drone, which face constraints such as limited turning radii. The algorithm integrates a novel edge detection process using off-the-shelf computer vision algorithms, enabling the identification and modification of water body edges for effective sensor coverage. The CPP algorithm is engineered to enhance coverage efficiency and mapping accuracy, adjusting swath orientation and length for optimal sonar sensor utilization. The CPP algorithm features the easy parameterization from users for tailored path planning and includes a heuristic method for path integration post swath computation, supported by a graphical user interface (GUI) for direct user modifications.  
[[Conference Paper]](https://arc.aiaa.org/doi/10.2514/6.2024-1204) 

<img src="/images/Newnans_path.png" width="350" /> 
<img src="/images/citra_mission.png" width="315" /> 

## Time and Cost-Efficient Bathymetric Mapping System using Sparse Point Cloud Generation and Automatic Object Detection 
**Andres Pulido**, Ruoyao Qin, Antonio Diaz, Andrew Ortega, Peter Ifju, Jane Shin.  
This paper introduces an efficient algorithm that generates a sparse 3D point cloud from side-scan sonar images. This computation is done in a computationally efficient manner by leveraging the geometry of the first sonar return combined with known positions provided by GPS and down-scan sonar depth measurement at each data point. Additionally, this paper implements another algorithm that uses YOLO, a Convolutional Neural Network (CNN) to perform object detection on side-scan sonar images collected in real life and generated with a simulation. The algorithm was tested on both real and synthetic images to show reasonably accurate anomaly detection and classification.  
[[Code]](https://github.com/andrespulido8/jupyter-notebooks/tree/aaa897c4248bb9b09f7f74eba1f3798313333720), [[Presentation]](/files/OCEANS-1.pdf), [[Preprint]](https://arxiv.org/abs/2210.10263), [[Conference Paper]](https://ieeexplore-ieee-org.lp.hscl.ufl.edu/document/9977073)

<img src="/images/oceans.png" width="550" /> 
<img src="/images/object_detection.png" width="550" /> 

## The Bathy-Drone: An Autonomous Uncrewed Drone-Tethered Sonar System
A. L. Diaz, A. Ortega, H. Tingle, **A. Pulido**, O. Cordero, M. Nelson, N. Cocoves, J. Shin, R. Carthy, B. Wilkinson, and P. Ifju.  
This paper introduces the Bathy-drone. The system provides both isobaths and contours of bottom hardness. Extensive testing of the system was conducted on a 5 acre pond located at the University of Florida Plant Science and Education Unit in Citra, FL. Prior to performing scans of the pond, ground-truth data were acquired with an RTK GNSS unit on a pole to precisely measure the location of the bottom at over 300 locations. An assessment of the accuracy and resolution of the system was performed by comparison to the ground-truth data. The pond ground truth had an average depth of 2.30 m while the Bathy-drone measured an average 21.6 cm deeper than the ground truth, repeatable to within 2.6 cm. The results justify integration of RTK and IMU corrections. During testing, it was found that there are numerous advantages of the Bathy-drone system compared to conventional methods including ease of implementation and the ability to initiate surveys from the land by flying the system to the water or placing the platform in the water. The system is also inexpensive, lightweight, and low-volume, thus making transport convenient.  
[[Paper]](https://www.mdpi.com/2504-446X/6/10/294) 

<img src="/images/bathydrone.gif" width="450" /> 