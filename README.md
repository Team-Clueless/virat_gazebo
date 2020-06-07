![alt text](https://img.shields.io/badge/status-stable-brightgreen)

# virat_gazebo

Gazebo simulation package for clueless virat :)


### virat_gazebo

  
* launch
  > launch files for worlds and bot
  
* models
  * model 1
    > files
  * model 2
    > files

* rviz
  > rviz config files
  
* worlds
  > world files

* src
  > any node files, (a teleop key maybe ?)


Notes
-----

* installed joint-state-pulisher-gui package for rviz

```bash
sudo apt install ros-kinetic-joint-state-publisher-gui
```

Usage
-----

### Launch virat in different worlds !

* Just the lanes, no barrels

```bash
roslaunch virat_gazebo igvc_basic.launch
```

* Lanes with barrels

```bash
roslaunch virat_gazebo igvc_world.launch
```

* Ramp world

```bash
roslaunch virat_gazebo igvc_ramp_world.launch
```

* Bounded world (custom made for debugging purposes)

```bash
roslaunch virat_gazebo virat_bounded_world.launch
```
