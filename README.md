# ROS 3D Robot Model example
## Run
1. Run ros core
~~~
roscore
~~~

2. Launch
"cd" to the model directory(below Denso-VS060)
~~~
cd vs060
~~~
and
~~~
roslaunch test.launch
~~~
"Joint State Publisher" will appear

3. Take a look
~~~
rviz
~~~
Then "Add" Robot into Displays items


## URDF modelling notice
1. Origin

The origin of the link(or arm) is joint to the parental link. The joint point to child link is represented by the origin of its joint

