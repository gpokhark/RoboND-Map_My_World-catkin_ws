# Getting Started
To view this project, you must have Gazebo and ROS installed on Linux.

With Gazebo and ROS installed follow the steps -
```
git clone git@github.com:gpokhark/RoboNd-ChaseIt-catkin_ws.git
cd RoboNd-ChaseIt-catkin_ws/
catkin_init_workspace
catkin_make
source devel/setup.bash
roslaunch my_robot world.launch
```

To make the robot chase the white ball, open another terminal, navigate to the top level catkin workspace, and execute:
```
source devel/setup.bash
roslaunch ball_chaser ball_chaser.launch
```

## Location os the ball to chase
[my_ball](./my_ball)