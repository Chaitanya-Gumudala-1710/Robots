![Screenshot from 2024-03-08 17-42-22](https://github.com/Chaitanya-Gumudala-1710/Robots/assets/84703770/ec20f2aa-94e0-4a44-bb3b-bf4b85956fe3)This repository is a collection of Universal Robot Description Format (URDF) files, of various robots I've designed while learning Robot Operating System (ROS).
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
![Differential Drive Robot_1](differential_drive_robot/images/differential_drive_robot_rviz.png)
![Differential Drive Robot_2](differential_drive_robot/images/differential_drive_robot_gazebo.png)

## Four wheel Drive Robot
To see the simulation of the four wheel robot in gazebo and rviz
```
ros2 launch four_wheel_robot four_wheel_robot_simulation.launch.py 
```
![Four Wheel Robot 1](four_wheel_robot/images/four_wheel_robot_rviz.png)
![Four Wheel Robot 2](four_wheel_robot/images/four_wheel_robot_gazebo.png)

## Arm
To see the simulation of the arm in gazebo and rviz
```
ros2 launch manipulator manipulator_simulation.launch.py 
```
![Manipulator 1](manipulator/images/manipulator.png)
![Manipulator 2](manipulator/images/manipulator.png)

## Mobile manipulator
To see the simulation of the mobile manipulator  in gazebo and rviz
```
ros2 launch mobile_manipulator mobile_manipulator_simulation.launch.py 
```
![Mobile Manipulator 1](mobile_manipulator/images/mobile_manipulator_rviz.png)
![Mobile Manipulator 2](mobile_manipulator/images/mobile_manipulator_gazebo.png)
