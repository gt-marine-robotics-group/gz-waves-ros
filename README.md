# gz-waves-ros

This project provides a ROS 2 wrapper for [ASV Wave Sim](https://github.com/srmainwaring/asv_wave_sim/tree/master?search=1), primarily providing quality-of-life streamlining of dependency installation and Gazebo hooks for ROS users. Please see the original repository for technical details.

## Install from source

Pull source code:
```
# Do this from the repository root directory
vcs import < gz-waves.repos
```

Install dependences via rosdep:
```
# Do this from your workspace (i.e. ros_ws)
rosdep install --from-paths src --ignore-src -r -y
```

Build:
```
colcon build --merge-install
```