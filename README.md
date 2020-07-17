# pyarm
Robotic arm control with ROS/Moveit

## Install Dependencies

To use this repositorie you need to install some dependencies, first you need ROS Melodic that you can install with the follow [instructions](http://wiki.ros.org/melodic/Installation/Ubuntu).

Another dependencie is MoveIt, and you can get with:

```
sudo apt-get install ros-melodic-moveit
```

To more informations of MoveIt follow the [Getting Started Guide](https://ros-planning.github.io/moveit_tutorials/)

## Usage

The basic usages of this repositories can be runed with the launch files in `pyarm_config/launch`.

For example, to run simulation in Gazebo you can use:

```
roslaunch pyarm_config gazebo.launch
```
