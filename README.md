# ROS 2 Simple Example

This is the very simple example for ROS 2 foxy.

# Build

* Setup ROS 2 foxy environment.

* Run the following commands.

```bash
mkdir -p ros2_example_ws/src
cd ros2_example_ws
wget https://raw.githubusercontent.com/Adlink-ROS/ros2_simple_example/main/examples.repos
vcs import src < examples.repos
colcon build
```

# Run

* C++ example

```bash
ros2 run cpp_pubsub talker
ros2 run cpp_pubsub listener
```

* Python example

```bash
ros2 run py_pubsub talker
ros2 run py_pubsub listener
```
