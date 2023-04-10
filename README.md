# ROS-1-simulated-robot.
This is a ROS 1  package that entails a simulated Robot called "Magum" which was created by a CAD software. It is integrated to work on SLAM and also Navigation (Mapping,Localization and Path Planning).

Creat a workspace and clone the package inro the src directory.
```
  mkdir -p ~/catkin_ws/src
```
Build the workspace.
```
 catkin_make 
```
clone the package into the src directory.
```
 cd src 
```

# LAUNCH THE ROBOT INTO GAZEBO WORLD.
```
 roslaunch Magnum_description emptyworld.launch 
```
