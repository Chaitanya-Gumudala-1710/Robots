This repository is a collection of Universal Robot Description Format (URDF) files, of various robots I've designed while learning Robot Operating System (ROS).
## Getting Started

### Cloning the Repository

To get started with the robots in this repository to your src
```
git clone https://github.com/Chaitanya-Gumudala-1710/Robots.git
```
### Building the Package
Open a terminal and build the package
```
colcon build
```

### Source the package
```
source install/localsetup.bash
```
## Differential Drive Robot
To see the simulation of the differential drive robot in gazebo and rviz
```
ros2 launch differential_drive_robot differential_robot_simulation.launch.py 
```
![Differential Drive Robot](differential_drive_robot/images/differential_drive_robot_rviz.png)
