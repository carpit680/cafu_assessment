# CAFU Technical Task

## Scenario

The simulation must have **4 Column** in an open space, and **3 separate** walls. Area must be
**10x10 meters**. Using the sensors, the Robot must follow the **GPS points (5 points will be enough)** to
reach the last one (Need to have ability to change the points during the simulation).
Robot must avoid the obstacles, if any, along the way.
Robot must create a SLAM map while running.
Please Explain all your decision about the Used Sensors and how the robot make decision to
avoid the obstacles

## Checklist

* ~~In the Gazebo simulation need to use the 3D model of the robot which will be provided.~~
* Need to Create a ROS node to control the provided 3Dmodel using a hardware joystick.
* Use the same node and setup to create a SLAM map.
* Need to Create a ROS node to automatically avoid the obstacles on the way.
* Need to Create a ROS node for GPS waypoint Navigation.
* Need to create the simulation in the Gazebo according by the provided scenario.
