# Extereoceptive_sensors_IGA

The Turtlebot model was taken from:

[Turtlebot](https://github.com/turtlebot/turtlebot)

## Create a workspace

`source /opt/ros/melodic/setup.bash`

`mkdir -p ~/turtlebot_ws/src`

`cd ~/turtlebot_ws/`

`catkin_make`

## Clone the repository into src

`cd src`

`git clone https://github.com/Andres12V/Extereoceptive_sensors_IGA.git`

## Launch the simulation in Gazebo and Rviz

`source devel/setup.bash`

`roslaunch turtlebot3_description spawn.launch`

### Yo sholud see something like this in Rviz:

![image](https://user-images.githubusercontent.com/73318612/138971962-e2ae5d31-ca09-4e7a-a72e-7aa391df850c.png)
