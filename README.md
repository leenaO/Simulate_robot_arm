Rviz and Gazebo simulators

Rviz
After download ROS, create a workspace, and install all packages that you need to execute and control robot arm you can use simulators such as Rviz to simulate the robot arm:
  •   To open the Rviz simulator Write the command below on the terminal:
             $ roslaunch robot_arm_pkg check_motors.launch
       o  The robot arm is visible but it can't move yet
  •   To move and control the robot arm use MoveIt software. Enter this command in the terminal to open it:
             $ roslaunch moveit_pkg demo.launch
       o To move the shoulder and elbow drag the arrow
       o To move the gripper move the ring in a circular motion
       
Gazebo
•     To open Gazebo enter this command:
           $ roslaunch robot_arm_pkg check_motors_gazebo.launch 

Rviz and Gazebo
•     To open Rviz and Gazebo use this command:
           $ roslaunch moveit_pkg demo_gazebo.launch


