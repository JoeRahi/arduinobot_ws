# 3DOF Manipulator ROS 2 Project

This repository contains a ROS 2 workspace for a 3-degree-of-freedom (3DOF) robotic manipulator, featuring simulation and visualization tools.

## Features

- **3DOF manipulator model** described using URDF/Xacro files
- Visualization using **RViz**
- Simulation environment setup in **Gazebo**
- Integrated **camera sensor** in the manipulator for perception tasks
- Example ROS 2 Python nodes demonstrating basic functionality

## Workspace Structure

- `src/arduinobot_description` — robot description including meshes and URDFs  
- `src/arduinobot_py_examples` — example Python nodes (publishers, subscribers, etc.)

## Usage

### Build the workspace

```bash
colcon build
source install/setup.bash
