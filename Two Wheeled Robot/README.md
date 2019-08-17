## Two Wheeled Robot

Creating a Two Wheeled Robot in ROS from scratch

### Visualization in RVIZ

Launch the Robot Model in RVIZ Environment using the following command

```roslaunch m2wr_description rviz.launch```

<p align="center">
  <img width="700" height="380" src="/Two Wheeled Robot/images/Visualization in RVIZ.png">
</p>

### Gazebo Simulator

Download the [Gazebo Simulator](http://wiki.ros.org/simulator_gazebo/Tutorials/StartingGazebo) for easier interation in the Gazebo Environment

#### Installation
```sudo apt-get install ros-%YOUR_ROS_DISTRO%-simulator-gazebo```

For kinetic and indigo, use the following command

```sudo apt-get install ros-kinetic-simulators```

#### Launching

```source /opt/ros/%YOUR_ROS_DISTRO%/setup.bash```

```roslaunch gazebo_worlds empty_world.launch```

For kinetic and indigo, use the following command

```roslaunch gazebo_ros empty_world.launch```

<p align="center">
  <img width="700" height="380" src="/Two Wheeled Robot/images/Gazebo Empty World.png">
</p>

### Visualization in Gazebo

Launch the Robot Model in Gazebo Environment using the following command

```roslaunch m2wr_description spawn.launch```

<p align="center">
  <img width="700" height="380" src="/Two Wheeled Robot/images/Visualization in Gazebo.png">
</p>

### References

- Basics of Robot Modeling using URDF [Part-1](http://www.theconstructsim.com/exploring-ros-2-wheeled-robot-part-01/)
