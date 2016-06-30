# modudculab_ros
---

modu dcu labs is a ROS package which will be used in the seminar for MAVROS and opensource quadrotors

## Install ROS
Ros installation [tutorials](http://wiki.ros.org/indigo/Installation/Ubuntu)


## Install Gazebo and gazebo_ros_pkgs
For installation instructions of gazebo, there is a [Tutorial](http://dev.px4.io/simulation-gazebo.html) in the px4 developer documentation page. 
- Install gazebo6

```
sudo apt-get update
sudo apt-get install gazebo6
# For developers that work on top of Gazebo, one extra package
sudo apt-get install libgazebo7-dev
```

- Install gazebo_ros_pkgs
The versions used is gazebo6. For instructions in using gazebo_ros_pkgs see [gazebo version guide](http://gazebosim.org/tutorials?tut=ros_wrapper_versions#Gazebo6.xseries)

```
apt-get install ros-indigo-gazebo6-ros-pkgs
```
## Install PX4
To install the PX4 app
```
mkdir -p ~/src
cd ~/src
git clone https://github.com/PX4/Firmware.git
cd Firmware
git submodule update --init --recursive
cd ..
```
Check if the repository can be properly built
```
cd ~/src/Firmware
make posix_sitl_default gazebo
```

## Install and build modudculab_ros
To install the package, clone from modudculab_ros repository
```
cd ~/catkin_ws/src
git clone https://github.com/Jaeyoung-Lim/modudculab_ros.git
catkin build modudculab_ros
```

