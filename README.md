# Quick Start within 3 Minutes 
Compiling tests passed on ubuntu **16.04, 18.04, and 20.04** with ros installed.
You can just execute the following commands one by one.

```
sudo apt-get install libarmadillo-dev
git clone https://github.com/LoriIp/fypDrone.git
cd fypDrone
catkin_make -j1
source devel/setup.bash
roslaunch ego_planner simple_run.launch
```
