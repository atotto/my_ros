# ROS

## usage

init:

```
$ vagrant up
$ vagrant ssh
$ echo "source /opt/ros/indigo/setup.bash" >> ~/.bashrc
$ source ~/.bashrc
```

## turtlesim

terminal1:

    $ roscore

terminal2:

    $ rosrun turtlesim turtlesim_node

terminal3:

    $ rosrun turtlesim turtle_teleop_key

