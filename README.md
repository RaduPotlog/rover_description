# rover_description

The package contains URDF files responsible for creating a representation of the robot.

## Launch Files

- `load_urdf.launch.py` - loads the robot's URDF and creates simple bindings to display moving joints.

## Launch

```bash
ros2 launch rover_description load_urdf.launch.py model:=urdf/rover_a1.urdf
```

## RViz: Rover


![Robot Model](images/rover_rviz.png)
