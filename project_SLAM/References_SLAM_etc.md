# References - SLAM (etc)

Revised on Mar 6 2021

<!-- 
######################################################################################################################################################
######################################################################################################################################################
-->
## Depth estimation

#### Depth completion
- Balanced Depth Completion between Dense Depth Inference and Sparse Range Measurements via KISS-GP
- Self-Supervised Sparse-to-Dense_Self-Supervised Depth Completion from LiDAR and Monocular Camera
- Learning Joint 2D-3D Representations for Depth Completion
- DeepLiDAR: Deep Surface Normal Guided Depth Prediction for Outdoor Scene from Sparse LiDAR Data and Single Color Image
- S3CNet: A Sparse Semantic Scene Completion Network for LiDAR Point Clouds


#### Depth estimation
- Digging Into Self-Supervised Monocular Depth Estimation
- Neural Ray Surfaces for Self-Supervised Learning of Depth and Ego-motion
- Dual CNN Models for Unsupervised Monocular Depth Estimation
- Unsupervised Monocular Depth Estimation with Left-Right Consistency
- PackNet-SfM: 3D Packing for Self-Supervised Monocular Depth Estimation
- FisheyeDistanceNet: Self-Supervised Scale-Aware Distance Estimation using Monocular Fisheye Camera for Autonomous Driving


#### Depth estimation/completion with something like ego-motion, flow, semantics...
- DF-Net: Unsupervised Joint Learning of Depth and Flow using Cross-Task Consistency
- Unsupervised Scale-consistent Depth and Ego-motion Learning from Monocular Video
- FuseNet: Incorporating Depth into Semantic Segmentation via Fusion-based CNN Architecture
- Simultaneous Semantic Segmentation and Depth Completion with Constraint of Boundary
- Sparse and Dense Data with CNNs: Depth Completion and Semantic Segmentation
- Semantic Segmentation of Urban Scenes Using Dense Depth Maps
<br/>
<br/>


<!-- 
######################################################################################################################################################
######################################################################################################################################################
-->
## DPC net (pose correction net)
- DPC-Net_Deep Pose Correction for Visual Localization
- Self-Supervised Deep Pose Corrections for Robust Visual Odometry
- Self-Supervised Scale Recovery for Monocular Depth and Egomotion Estimation
<br/>
<br/>


<!-- 
######################################################################################################################################################
######################################################################################################################################################
-->
## LiDAR-based localization
- DH3D: Deep Hierarchical 3D Descriptors for Robust Large-Scale 6DoF Relocalization
<br/>
<br/>


<!-- 
######################################################################################################################################################
######################################################################################################################################################
-->
## [Base] Pose graph

#### Paper
- Factor graph based incremental smoothing in inertial navigation systems
- Factor graphs for robot perception
- Information fusion in navigation systems via factor graph based incremental smoothing
- Solution to the SLAM problem in low dynamic environments using a pose graph and an RGB-D sensor
- [Study on the use of vision and laser range sensors with graphical models for the SLAM problem](https://tel.archives-ouvertes.fr/tel-01676275v2/document)

#### Material
- [UAL course on factor graph](https://github.com/jlblancoc/2020-ual-factor-graphs-course)
<br/>
<br/>


<!-- 
######################################################################################################################################################
######################################################################################################################################################
-->
## [Base] IMU Preintegration

- [A general optimization-based framework for local odometry estimation with multiple sensor](https://arxiv.org/abs/1901.03638)
  - Code: https://github.com/HKUST-Aerial-Robotics/VINS-Fusion
  <!-- Clearly, stating that 'Within two time instants, t-1 and t, the preintegration produces relative position, velocity and rotation'. -->
- [IMU preintegration for visual-inertial odometry pose estimation](https://www.semanticscholar.org/paper/IMU-Preintegration-for-Visual-Inertial-Odometry-Liu-Su/23845719d3325763b886ffdba7ac2bdeb2790483)
  
#### Guoquan Huang's group
- [Visual-inertial navigation: a concise review](https://arxiv.org/pdf/1906.02650.pdf)
- [Robocentric visual-inertial odometry](https://arxiv.org/pdf/1805.04031.pdf)
- [Continuous preintegration theory for graph-based visual-inertial navigation](https://arxiv.org/pdf/1805.02774.pdf)
- [Closed-form preintegration methods for graph-based visual-inertial navigation](https://arxiv.org/pdf/1805.02774.pdf)
- [High-accuracy preintegration for visual inertial navigation](http://udel.edu/~ghuang/papers/tr_hapi.pdf)

#### Base
- Visual-inertial-aided navigation for high-dynamic motion in built environments without initial conditions
- Eliminating conditionally independent sets in factor graphs: a unifying perspective based on smart factors
- IMU preintegration on manifold for efficient visual-inertial maximum-a-posteriori estimation
- [The preintegrated IMU factor in GTSAM](https://gtsam.org/notes/IMU-Factor.html)

#### Etc
- [Accurate imu preintegration using switched linear systems for autonomous systems](https://arxiv.org/pdf/1907.08434.pdf)
- [Fast and robust monocular visua-inertial odometry using points and lines](https://www.researchgate.net/publication/336693512_Fast_and_Robust_Monocular_Visua-Inertial_Odometry_Using_Points_and_Lines)
- [A real-time sliding window based visual-inertial odometry for MAVs](https://ieeexplore.ieee.org/document/8931626)
- [Adaptive monocular visual–inertial slam for real-time augmented reality applications in mobile devices](https://www.mdpi.com/1424-8220/17/11/2567)
- [Using inertial sensors for positionand orientation estimation](https://arxiv.org/pdf/1704.06053.pdf)
<br/>
<br/>


<!-- 
######################################################################################################################################################
######################################################################################################################################################
-->
## Etc

#### Paper
- [Spatiotemporal Camera-LiDAR Calibration:A Targetless and Structureless Approach](https://arxiv.org/abs/2001.06175?fbclid=IwAR2alEbmlpDjdJ7HIrBn-046y7jsfKkMifauZV6YQnZ42QoPQIZD5pXo73w)
- Comparison of various SLAM systems for mobile robot in an indoor environment

#### Course
- [Course lecture on visual inertial fusion (by Davide Scaramuzza)](http://rpg.ifi.uzh.ch/docs/teaching/2019/13_visual_inertial_fusion.pdf)
- [Structure from Motion (in CMSC426 Computer Vision)](https://cmsc426.github.io/gtsam/)

#### Material
- [Towards robust and safe autonomous drones](https://www.slideshare.net/SERENEWorkshop/towards-robust-and-safe-autonomous-drones)
- [Description of VINS-Mono](https://alexanderhmw.blog/2018/04/24/vins-mono-a-robust-and-versatile-monocular-visual-inertial-state-estimator-3/)
<br/>
<br/>


