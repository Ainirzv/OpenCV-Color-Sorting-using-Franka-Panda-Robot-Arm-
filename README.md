# Franka Panda Robot - ROS 2 Workspace

ROS 2 workspace containing the Franka Panda robot description and controller configuration.

## Packages

- `panda_description`: Robot URDF/Xacro files, meshes, RViz configuration, launch files, and simulation assets.
- `panda_controller`: Controller configuration and launch files.

## Build

```
cd ~/panda_ws
source /opt/ros/humble/setup.bash
colcon build
source install/setup.bash
```

## Current status
Robot description and controller setup are included. OpenCV color detection and automated color sorting are not yet included.
