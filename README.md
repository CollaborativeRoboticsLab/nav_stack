# nav_stack

## Install Navigation stack

```bash
sudo apt install ros-$ROS_DISTRO-navigation2 ros-$ROS_DISTRO-nav2-bringup
```

## Install SLAM toolbox for SLAM (AMCL)

```bash
sudo apt install ros-$ROS_DISTRO-slam-toolbox
```

## Launch Nav2

```bash
ros2 launch nav2_bringup navigation_launch.py
```

## Launch SLAM

```bash
ros2 launch slam_toolbox online_async_launch.py
```