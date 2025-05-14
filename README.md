# DHBW-Robotik-Uebungen

This Repository is part of an lecture from Mark Geiger which can be found in his Repository on GitLab: <https://gitlab.com/MarkGeiger/robotik>

## Start ROS:
```bash
source /opt/ros/jazzy/setup.bash
```

## test / start rviz:
```bash
ros2 run rviz2 rviz2
```

## launch gazebo:
```bash
gz sim
```
```bash
gz sim empty.sdf
```
oder:
```bash
ros2 launch ros_gz_sim gz_sim.launch.py gz_args:=empty.sdf
```
