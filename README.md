# rover_description

The package contains URDF files responsible for creating a representation of the robot.

## Config Files

- `wheel_01.yaml` - Rover 4WD (33 inch) wheel configuration.

- `components.yaml` - Rover additional components configuration.

## Launch Files

- `rover_load_urdf.launch.py` - Loads the robot's URDF and creates simple bindings to display moving joints.

## Running

```bash
ros2 launch rover_description rover_load_urdf.launch.py
```

```bash
ros2 launch rover_description rover_rviz.launch.py
```

```bash
 ros2 run joint_state_publisher_gui joint_state_publisher_gui
```

## RViz

![Robot Model](images/rover_rviz.png)

## Gazebo
-