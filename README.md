# Launch-TurtleBot-navigation

## Install TurtleBot3 Packages

$ sudo apt install ros-noetic-dynamixel-sdk

$ sudo apt install ros-noetic-turtlebot3-msgs

$ sudo apt install ros-noetic-turtlebot3

![1](https://github.com/user-attachments/assets/a4112dba-1c0a-4168-ae4b-8eea745f61a7)
#

## Launch Simulation World

$ export TURTLEBOT3_MODEL=waffle

$ roslaunch turtlebot3_gazebo turtlebot3_world.launch

![2](https://github.com/user-attachments/assets/10b2ccbd-88af-46a8-9f40-642b3db514c5)
#

## SLAM , Navigation
Type the following commands: 

$ ls -l

$ mkdir -p ~/test_turtlebot3/src

$ ls -l

$ cd ~/test_turtlebot/src

$ ls -l

$ git clone https://github.com/ROSBOTIS-GIT/turtlebot3.git

$ git clone https://github.com/ROSBOTIS-GIT/turtlebot3_msgs.git

$ git clone https://github.com/ROSBOTIS-GIT/turtlebot3_simulation.git

$ Catkin_make

![3](https://github.com/user-attachments/assets/67b3bec5-f9a9-4760-87c2-d56d9bbfc46b)
#

### Then open another terminal window and type:
$ source ~/test_turtlebot/devel/setup.bash 

$ export TURTLEBOT3_MODEL=burger

$ roslaunch turtlebot3_teleop turtlebot3_teleop_key.launch

![4](https://github.com/user-attachments/assets/cb295e32-1e1d-4865-a43a-1403fa76ae3e)
#

Will appear

![5](https://github.com/user-attachments/assets/6e9a7129-de83-4acd-aa8c-77f6fdf29ac3)
#

You can also move it

![6](https://github.com/user-attachments/assets/ff998158-cbd5-49ef-9b66-749d5eb80dd9)
#

## I tried more than one method and none worked for me except this method. I hope it is correct, Thank you.














