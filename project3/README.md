# CSE598 Perception in Robotics (Spring 2020) Project 3
## Pursuit Evasion Game
This repository contains the package(s) for project 3.

It depends and follows similar paradigms to the upstream turtlebot3 package from ROBOTIS.

## File Structure
For convenience,the upstream turtlebot3 and turtlebo3_msgs packages from ROBOTIS-GIT/turtlebot3 are bundled.

```
src/
├── project3
│   └── pursuitevasion
├── turtlebot3
│   ├── turtlebot3
│   ├── turtlebot3_bringup
│   ├── turtlebot3_description
│   ├── turtlebot3_example
│   ├── turtlebot3_navigation
│   ├── turtlebot3_slam
│   └── turtlebot3_teleop
└── turtlebot3_msgs
    └── msg
```

### Building
Clone to the `src/` directory of your catkin workspace, then run `catkin_make` from the latter.

### Running
`source devel/setup.bash`

To start the gazebo simulation, run `roslaunch pursuitevasion pursuitevasion_world.launch`

To start an rviz instance run `roslaunch pursuitevasion pursuitevasion_gazebo_rviz.launch`

To run the navigation node, run `rosrun pursuitevasion navigate`
