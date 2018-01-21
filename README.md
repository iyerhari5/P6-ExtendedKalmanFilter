# Extended Kalman Filter Project

The goal of this project is to implement an Extended Kalaman Filter using Radar and Lidar measurements.

## Project Structure

The crux of the code is implemented in 3 files:

FusionEKF.cpp
kalman_filter.cpp
Tools.cpp


FusionEKF: This is the module that is responsible for initializing and calling the kalaman filter prediction and update functions 
based on the type of the input measurement. The inpupts can be either from a Radar or from a Lidar

kalaman_filter.cpp: This is the module that implements the kalman filtering algorithms - both the linear case(Lidar) and the non linear case (Radar)
 for the 
