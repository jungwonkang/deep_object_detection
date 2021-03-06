# References - SLAM2

Started to write on Jan 7 2020
<br/>
### Overview
- [Visual Odometry and SLAM: past, present, and the robust-perception age (by Davide Scaramuzza)](https://www.rsj.or.jp/databox/international/iros16tutorial_2.pdf)
- [Description of VINS-Mono](https://alexanderhmw.blog/2018/04/24/vins-mono-a-robust-and-versatile-monocular-visual-inertial-state-estimator-3/)
- [Towards Robust and Safe Autonomous Drones](https://www.slideshare.net/SERENEWorkshop/towards-robust-and-safe-autonomous-drones)
- [Structure from Motion (in CMSC426 Computer Vision)](https://cmsc426.github.io/gtsam/)
- [Course lecture on visual inertial fusion (by Davide Scaramuzza)](http://rpg.ifi.uzh.ch/docs/teaching/2019/13_visual_inertial_fusion.pdf)
- [Perception and Decision-Making of Autonomous Systems in the Era of Learning: An Overview](https://arxiv.org/abs/2001.02319)
  - Providing a comprehensive review of the current state-of-the-art SLAM
- [Keyframe-based monocular SLAM: design, survey, and future directions](https://arxiv.org/pdf/1607.00470.pdf)
- [Past, present, and future of SLAM: towards the robust-perception age](https://arxiv.org/pdf/1606.05830.pdf)
- [Simultaneous localization and mapping: a survey of current trends in autonomous driving](https://hal.archives-ouvertes.fr/hal-01615897/file/2017-simultaneous_localization_and_mapping_a_survey_of_current_trends_in_autonomous_driving.pdf)
<br/>
<br/>


### IMU Preintegration
*Clearly stated*
- [A general optimization-based framework for local odometry estimation with multiple sensor](https://arxiv.org/abs/1901.03638)
  - Code: https://github.com/HKUST-Aerial-Robotics/VINS-Fusion
  <!-- Clearly, stating that 'Within two time instants, t-1 and t, the preintegration produces relative position, velocity and rotation'. -->
- [IMU preintegration for visual-inertial odometry pose estimation](https://www.semanticscholar.org/paper/IMU-Preintegration-for-Visual-Inertial-Odometry-Liu-Su/23845719d3325763b886ffdba7ac2bdeb2790483)
  
*Guoquan Huang's group*
- [Visual-inertial navigation: a concise review](https://arxiv.org/pdf/1906.02650.pdf)
- [Robocentric visual-inertial odometry](https://arxiv.org/pdf/1805.04031.pdf)
- [Continuous preintegration theory for graph-based visual-inertial navigation](https://arxiv.org/pdf/1805.02774.pdf)
- [Closed-form preintegration methods for graph-based visual-inertial navigation](https://arxiv.org/pdf/1805.02774.pdf)
- [High-accuracy preintegration for visual inertial navigation](http://udel.edu/~ghuang/papers/tr_hapi.pdf)

*Base*
- Visual-inertial-aided navigation for high-dynamic motion in built environments without initial conditions
- Eliminating conditionally independent sets in factor graphs: a unifying perspective based on smart factors
- IMU preintegration on manifold for efficient visual-inertial maximum-a-posteriori estimation
- [The preintegrated IMU factor in GTSAM](https://gtsam.org/notes/IMU-Factor.html)

*Etc*
- [Accurate imu preintegration using switched linear systems for autonomous systems](https://arxiv.org/pdf/1907.08434.pdf)
- [Fast and robust monocular visua-inertial odometry using points and lines](https://www.researchgate.net/publication/336693512_Fast_and_Robust_Monocular_Visua-Inertial_Odometry_Using_Points_and_Lines)
- [A real-time sliding window based visual-inertial odometry for MAVs](https://ieeexplore.ieee.org/document/8931626)
- [Adaptive monocular visual–inertial slam for real-time augmented reality applications in mobile devices](https://www.mdpi.com/1424-8220/17/11/2567)
- [Using inertial sensors for positionand orientation estimation](https://arxiv.org/pdf/1704.06053.pdf)
<br/>
<br/>


### Pose graph
- Factor graph based incremental smoothing in inertial navigation systems
- Factor graphs for robot perception
- Information fusion in navigation systems via factor graph based incremental smoothing
- Solution to the SLAM problem in low dynamic environments using a pose graph and an RGB-D sensor
- [Study on the use of vision and laser range sensors with graphical models for the SLAM problem](https://tel.archives-ouvertes.fr/tel-01676275v2/document)
<br/>
<br/>


### Visual-LiDAR SLAM
- [Vision-enhanced LiDAR odometry and mapping (Master's thesis, Carnegie Mellon University)](https://www.ri.cmu.edu/pub_files/2016/8/DLL-thesis.pdf)
- [A real-time method for depth enhanced visual odometry](https://frc.ri.cmu.edu/~zhangji/publications/AURO_2017.pdf)
- [LIMO: LiDAR monocular visual odometry](https://arxiv.org/pdf/1807.07524.pdf)
- DVL-SLAM: Sparse depth enhanced direct visual-LiDAR SLAM
<br/>
<br/>


### Useful link
- [SLAM KR youtube channel (in Korean)](https://www.youtube.com/channel/UCXvT7auo7xUd7v0B2pmvwIA)
<br/>


### Etc
- [Spatiotemporal Camera-LiDAR Calibration:A Targetless and Structureless Approach](https://arxiv.org/abs/2001.06175?fbclid=IwAR2alEbmlpDjdJ7HIrBn-046y7jsfKkMifauZV6YQnZ42QoPQIZD5pXo73w)
- [A Modular Optimization Framework for Localization and Mapping](http://www.roboticsproceedings.org/rss15/p43.pdf)
  - github: https://github.com/MOLAorg/mola
  - presentation: https://youtu.be/qwh8hGEJSlA
- [UAL course on factor graph](https://github.com/jlblancoc/2020-ual-factor-graphs-course)
<br/>


