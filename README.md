# jackal
======

Common packages for Jackal, including messages and robot description. These are packages relevant
to all Jackal workspaces, whether simulation, desktop, or on the robot's own headless PC.

## Additional dependencies

Please run the below commands for resolving additional dependencies
```
cd ~/$(YOUR_WORKSPACE)/src
git clone https://github.com/Gyuhub/realsense_gazebo_plugin
cd ../ && catkin_make # or catkin build
source devel/setup.bash
rosdep install --from-paths src --ignore-src
```