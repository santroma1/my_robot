# my_robot

## Simple GAZEBO robot + world

This is a simple differential drive robot that is housed in a custom world.
Robot contains a camera and a LIDAR sensor.

Robot can be driven by publishing to velocity topic.
Images from a camera on the robot are also published to an Image topic.

In collaboration with the ball_chaser package, the robot follows a white ball given the image posted by the camera.


### Installation

Full ROS desktop installation is required.


Clone to your catkin_ws/src folder and compile for it to run.
