# turtlebot_vacuum
[![GitHub license](https://badgen.net/github/license/Naereen/Strapdown.js)](LICENSE.md)

This repository contains a ROS programs that can control the robot and modifies the behavior of turtlebot3 to behave like a roomba. Launch files are also included for both the operations.

## Dependencies
* Ubuntu 20.04
* ROS (Noetic preferred)
* turtlebot3 libraries
* Gazebo

## Usage

### Downloading the repository

First clone the repository
```
git clone https://github.com/pratik-a99/autonomous-robot-690.git
```

### Adding it to ROS workspace
Then, add the downloaded repository into your ROS workspace's src folder (eg. catkin_make/src)
```
cd ~/carkin_ws/src
```
To build the changes use
```
cd ..
catkin_make
```

#### Launch files

To use the launch file for controlling the robot, use the following command in a terminal
```
roslaunch turtlebot_vacuum turtlebot_teleop.launch 
```

To use the launch file for autonomous robot, use the following command in a terminal

```
roslaunch turtlebot_vacuum turtlebot_autonomous.launch
```

## Videos

The videos of the simulation are present in the 'videos' folder.

