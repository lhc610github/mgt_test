# lu_test
This package is an example for testing [mav_trajectory_generation](http://github.com/ethz-asl/mav_trajectory_generation)
## linear optimization test
```
catkin build mav_trajectory_generation 
catkin build lu_test  
roscore
rosrun lu_test linear_traject_test
roscd lu_test/launch/
roslaunch rviz.launch
```
