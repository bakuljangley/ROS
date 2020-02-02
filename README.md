# ROS

To get the STDR simualtor working : 

# Install the Simulator ( Build from Source ) : 

Reference link : http://wiki.ros.org/stdr_simulator/Tutorials/Set%20up%20STDR%20Simulator

```bash
cd <your_catkin_ws>/src
git clone https://github.com/stdr-simulator-ros-pkg/stdr_simulator.git
cd ..
rosdep install --from-paths src --ignore-src --rosdistro $ROS_DISTRO
catkin_make
```

# Source Environment variables 

Reference Link : http://wiki.ros.org/ROS/Tutorials/CreatingPackage

If you are using ZSH then it is differenet , but if you are sure what shell you are in , then it's probably bash , so you can run the command below.

```bash
. ~/catkin_ws/devel/setup.bash
```

# Run the Example 

Reference Link : http://wiki.ros.org/stdr_simulator/Tutorials/Running%20STDR%20Simulator

Run this from the Source Directory :


```bash
roslaunch stdr_launchers server_with_map_and_gui_plus_robot.launch
```
