# teleop_twist_keyboard
Generic Keyboard Teleop for ROS
#Launch
To run: `rosrun teleop_twist_keyboard teleop_twist_keyboard.py`

#Usage
```
Reading from the keyboard  and Publishing to Twist!
---------------------------
Moving around:
        w
   a    s    d

Rotation:
---------------------------
CCW: q
CQ:  e

Elevation:
---------------------------
r : up (+z)
f : down (-z)

anything else : stop

t/y : increase/decrease max speeds by 10%
g/h : increase/decrease only linear speed by 10%
b/n : increase/decrease only angular speed by 10%

CTRL-C to quit
```

