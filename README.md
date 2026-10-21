# Franka Panda Robot - ROS 2 Workspace

ROS 2 workspace containing the Franka Panda robot description and controller configuration.
<img width="1600" height="1000" alt="image" src="https://github.com/user-attachments/assets/94237fab-470f-4f00-bcfa-ef33aefecef7" />


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
