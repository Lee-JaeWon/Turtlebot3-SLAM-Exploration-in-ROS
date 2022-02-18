# Turtlebot3-SLAM-Exploration-in-ROS

## 1. explore_lite with gmapping
### 1-1. Requirements
```
$ sudo apt install ros-melodic-multirobot-map-merge ros-melodic-explore-lite
```

### 1-2. excute _ `.launch` file
`roslaunch ros_slam_exploration explore_turtlebot3_fake.launch`<br>

### 1-3. Reference
[ROS : explore_lite](http://wiki.ros.org/explore_lite)<br>
greedy frontier-based exploration

<br><br>

---
## Reference
[Robotis/turtlebot3/sitmulation](https://emanual.robotis.com/docs/en/platform/turtlebot3/simulation/)<br>
[https://github.com/ROBOTIS-GIT/turtlebot3_simulations.git](https://github.com/ROBOTIS-GIT/turtlebot3_simulations.git)

## Requirements
```
$ sudo apt-get install ros-melodic-joy ros-melodic-teleop-twist-joy \
  ros-melodic-teleop-twist-keyboard ros-melodic-laser-proc \
  ros-melodic-rgbd-launch ros-melodic-depthimage-to-laserscan \
  ros-melodic-rosserial-arduino ros-melodic-rosserial-python \
  ros-melodic-rosserial-server ros-melodic-rosserial-client \
  ros-melodic-rosserial-msgs ros-melodic-amcl ros-melodic-map-server \
  ros-melodic-move-base ros-melodic-urdf ros-melodic-xacro \
  ros-melodic-compressed-image-transport ros-melodic-rqt* \
  ros-melodic-gmapping ros-melodic-navigation ros-melodic-interactive-markers
```
```
$ sudo apt-get install ros-melodic-turtlebot3-msgs
$ sudo apt-get install ros-melodic-turtlebot3
```
```
$ sudo apt-get install ros-melodic-navigation
```
```
$ sudo apt-get install ros-melodic-gazebo-ros-pkgs ros-melodic-gazebo-ros-control
```