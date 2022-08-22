# camera_overall

## Overview
This package is the combination of two packages, [object_tracker](https://github.com/gmkim97/object_tracker.git) and [marker_detection](https://github.com/gmkim97/ArUco_marker_detection.git).

## Dependencies
- Ubuntu 20.04 LTS (Focal Fossa)
- Robotic Operating System([ROS](http://wiki.ros.org/ROS/Installation)) noetic

To activate it, you will need
- Realsense SDK 2.0
- Realsense ROS package
- OpenCV4
- [darknet_ros](https://github.com/leggedrobotics/darknet_ros)

## Notice
The script in this package is tested on **python3** environment

## Installation
```
$ cd ~/catkin_ws/src/
$ git clone https://github.com/gmkim97/camera-overall
(OR https://github.com/CoMoBot-Perception/camera-overall)
(OR https://github.com/CoMoBi-Overall/Camera.git)
$ cd ~/catkin_ws/
$ catkin_make
```

## How to start?
```
$ roslaunch camera_overall camera_overall.launch
```