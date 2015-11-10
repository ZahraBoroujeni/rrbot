# rrbot
Comprehensive example to show recent capabilities in ROS/Gazebo/MoveIt!

## Dependencies

## Uses

* Bring up the __single_rrbot__ robot (it loads the simulated one by default):

`roslaunch rrbot_launch bringupRRBOT.launch`

* Move the __single_rrbot__ robot using `ros-controls`

Launch `rqt`, and open Plugins->Robot Tools->Joint trajectory controller and move the robot with slides.

* Move the __single_rrbot__ robot using MoveIt!

Install necessary packages like:

`sudo apt-get install ros-indigo-ompl-visual-tools 
 sudo apt-get install ros-indigo-moveit-ros-*`

Load the planning environment:


`roslaunch single_rrbot_moveit_config move_group.launch`

Open the pre-configured rviz and use the MoveIt! display:

`roslaunch single_rrbot_moveit_config moveit_rviz.launch`
