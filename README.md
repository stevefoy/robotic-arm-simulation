# robotic-arm-simulation



#### Usage
Install dependencies:
```
rosdep install --from-paths src --ignore-src -r -y
```
Build catkin workspace:
```
catkin_make
```
Init the environment:
```
source devel/setup.sh
```
Launch the gazebo simulation:
```
roslaunch arm_gazebo empty_world.launch
```
Launch the controller along with RViz:
```
roslaunch arm_control rviz.launch
```
Launch the MoveIt! move group:
```
roslaunch arm_control moveit.launch
```
You can now use the MoveIt! plugin in Rviz to control the arm.
___
