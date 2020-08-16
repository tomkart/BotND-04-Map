# BotND-03-Where

Project: Where Am I

**To run**

```
cd ~/BotND-03-Where
catkin_make
source devel/setup.bash
roslaunch my_robot world.launch 
```

Open another terminal

```
cd ~/BotND-03-Where
source devel/setup.bash
roslaunch my_robot amcl.launch
```

The map should appear in rviz now

Open another terminal
```
cd ~/BotND-03-Where
source devel/setup.bash
rosrun teleop_twist_keyboard teleop_twist_keyboard.py 
```
Use keyboard to control the robot to go around the room 

**Result**



