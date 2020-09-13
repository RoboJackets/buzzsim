# buzzsim
This repo contains Buzzsim, a turtlesim-esque environment that contains sensors such as a lidar and imu.

## Getting Started
Clone the repo into a catkin workspace:
```bash
cd catkin_ws # cd to where your catkin workspace is located
cd src
git clone https://github.com/RoboJackets/buzzsim.git
```

Install dependencies:
```bash
sudo apt install libcgal-dev
cd catkin_ws # cd to where your catkin workspace is located
rosdep install --from-paths src --ignore-src -y
```

Build the simulator and the exercises:
```bash
cd catkin_ws # cd to where your catkin workspace is located
catkin_make
```