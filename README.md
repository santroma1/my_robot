# my_robot

## Simple GAZEBO robot + world

This is a simple differential drive robot that is housed in a custom world.
Robot contains a camera and a LIDAR sensor.

Robot can be driven by publishing to velocity topic.
Images from a camera on the robot are also published to an Image topic.

In collaboration with the ball_chaser package, the robot follows a white ball given the image posted by the camera.

## Branch PROJECT3 - AMCL
Switching to branch "PROJECT3" is a ROS package in which there is 2 launch files, the first one is the world.launch which runs Gazebo and the original world with the robot. In this branch the RVIZ is configured to work with AMCL.

Then if you run the Adaptive Monte Carlo Localization launch file, amcl.launch, in RVIZ the AMCL particles can be seen, visualizing the robot.

Then run the teleop node to control the robot.

### Installation

Full ROS desktop installation is required.


Clone to your catkin_ws/src folder and compile for it to run.
