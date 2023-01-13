# Quick Start within 3 Minutes 

install ROS noetic on ubuntu 20.04
```
http://wiki.ros.org/noetic/Installation/Ubuntu
```
Then, You can just execute the following commands one by one.
```
sudo apt-get install libarmadillo-dev
git clone https://github.com/LoriIp/fypDrone.git
cd fypDrone
catkin_make -j1
source devel/setup.bash

```
open the rviz for visualization and interactions

```
source devel/setup.bash
roslaunch ego_planner rviz.launch

```

In another terminal, run the planner in simulation by
```
source devel/setup.bash
roslaunch ego_planner swarm.launch
```
