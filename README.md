# SOFAR_Object_Following_Robot
This is the final Assignment of the our course Software Architectures for Robotics (SofAR) in which we are asked to build a simulation with ROS in which a robot follows
a moving target (e.g., a person or another robot) at a fixed distance.

## Two methods were Implemented in this case
* Using nav2
* Using OpenCV

## Nav2
Intially installed the Nav2 pkg  which is used in ROS2 for the navigation of robots in the environment. We used spacific part of the nav2 to the simulation to implement the  "following dynamic point" maintaining a fixed distance.


![14c633ce-da26-44c6-8ab1-409e551f2424](https://user-images.githubusercontent.com/105802251/211937880-61b5d775-c529-4a37-bd1c-de328b86b204.jpg)


Basiclly here we use Nav2 for a task going from point A to point B. In this case, we will use Nav2 to follow a moving object at a spacified distance, the point changes continously and updates the goal to the robot and makes it to moves in given direction.This task is useful in cases such as robot following a person (suitcase follows you as you walk) or another robot.
