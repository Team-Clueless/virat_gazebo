# virat_gazebo

gazebo simulation package for clueless virat :)

Structuring of this package is done keeping the turtlebot3_gazebo package as a reference (atleast for now)
Please make changes keeping in mind the following structure

virat_gazebo

* include
  > contains any header files or python modules (if any)
  
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

Pending tasks
-------------

- [ ] Update model.sdf of virat according to the virat_urdf file
- [ ] Add lidar prototype in both urdf and sdf
- [ ] Tweak the inertia values

Notes
-----

* installed joint-state-pulisher-gui package for rviz

```bash
sudo apt install ros-kinetic-joint-state-publisher-gui
```
