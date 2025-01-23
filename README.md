# DNN based Virtual Trajectory Generation for Autonomous Vehicles: Focus on Local Reference Path Computation

This implementation focuses on generating a local reference path for lane-keeping of autonomous vehicles based on sequential past road lane data. It demonstrates the effectiveness of the trained model from developed VTG Framework, producing robust trajectories under varying conditions, including scenarios with missing lanes, noise, or sensor inaccuracies. By embedding this workflow in CARLA’s simulation environment, it enables rigorous testing of the model’s performance in controlled yet realistic conditions. 

Author: Sarvesh Telang. telang@rptu.de

Vehicle Simulation Video: https://seafile.rlp.net/lib/7e890b82-073a-400a-8e59-0bb07fe0a2ae/file/Lane_Prediction_1_LH0.5.mp4

![Simulation Demo](Vehicle_Simulation_Demo.gif)

More Videos: https://seafile.rlp.net/library/7e890b82-073a-400a-8e59-0bb07fe0a2ae/VTG_Vehicle_Simulation_Videos/

The following figures provide an overview of the overall pipeline of the work.

![Overall Pipeline](Thesis_Implementation_Pipeline.png)

![Carla Implementation](Simulation_over_CARLA.png)

=============================================================================================

Previous work:

Image based lane detection is performed using DNN model. 

The model is based on Ultra Fast Structure-aware Deep Lane Detection. Link: https://arxiv.org/abs/2004.11757 

Lane keeping is based on Kinematic iMPC framework: S. A. Hiremath, P. K. Gummadi and N. Bajcinca, "Image based Model Predictive Controller for Autonomous Driving". Link: https://ieeexplore.ieee.org/document/10185808
