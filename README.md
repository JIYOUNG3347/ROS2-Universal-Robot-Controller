# ros2_ur_controller


### Universal Robot Contorller Launch
https://github.com/UniversalRobots/Universal_Robots_ROS2_Driver.git

   ```
   ros2 launch ur_bringup ur_control.launch.py ur_type:=ur5e robot_ip:=yyy.yyy.yyy.yyy robot_controller:=scaled_joint_trajectory_controller use_fake_hardware:=true launch_rviz:=true
   ```

### Launch subscriber
   ```
    ros2 run py_pubsub my_subscriber
   ```
   
### Launch publiser
   ```
    ros2 run py_pubsub my_publisher
   ```
   
### rqt_graph
![Untitled](https://user-images.githubusercontent.com/77952928/229437353-059903d6-cbe1-44d9-acac-f00ddcbc7bb1.png)
