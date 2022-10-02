# flocking_motion ROS package

## Requirements
- ROS -- tested on Melodic, but other versions may work.
- catkin -- used for building the application. 

## Build
  cd catkin_ws/src
  git clone git@github.com:chenmasterandrew/flocking_motion.git
  git clone git@github.com:ros-simulation/stage_ros.git
	cd catkin_ws
	catkin_make
	
## Run in Gazebo
	source catkin_ws/devel/setup.sh
	roslaunch flocking_motion flocking_motion_gazebo.launch 

## Run in Stage
	source catkin_ws/devel/setup.sh
	roslaunch flocking_motion flocking_motion_stage.launch 

## Attribution & Licensing

See LICENSE for further information
