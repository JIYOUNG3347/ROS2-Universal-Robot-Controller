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
![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b5a3c941-3608-484b-b704-55786d8adc6a/Untitled.png)
