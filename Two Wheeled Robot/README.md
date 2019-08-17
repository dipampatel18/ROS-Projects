## Two Wheeled Robot

Creating a Two Wheeled Robot in ROS



Download the [Gazebo Simulator](http://wiki.ros.org/simulator_gazebo/Tutorials/StartingGazebo) for easier interation in the Gazebo Environment

#### Installation
```sudo apt-get install ros-%YOUR_ROS_DISTRO%-simulator-gazebo
```

For kinetic and indigo, use the following command
```sudo apt-get install ros-kinetic-simulators
```

#### Launching

```source /opt/ros/%YOUR_ROS_DISTRO%/setup.bash
```

```roslaunch gazebo_worlds empty_world.launch
```

For kinetic and indigo, use the following command
```roslaunch gazebo_ros empty_world.launch
```

### References

[Part-1](http://www.theconstructsim.com/exploring-ros-2-wheeled-robot-part-01/)
