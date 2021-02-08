# ROS 2 Simple Example

This is the very simple example for ROS 2.

# Build

```bash
mkdir -p ros2_example_ws/src
cd ros2_example_ws
wget https://raw.githubusercontent.com/Adlink-ROS/ros2_simple_example/main/examples.repos
vcs import src < examples.repos
colcon build
```
