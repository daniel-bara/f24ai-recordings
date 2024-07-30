Here you will find rosbag recorded during the F24 Silverstone event (skidpad and acceleration not recorded).

/tf was not recorded, so /odom does not relate to /world. To visualise the odometry and other topics on the same screen, use the following:\
``` rosrun tf2_ros static_transform_publisher 0 0 0 0 0 0 /world /odom ```

The preset Rviz display setting from gra can be used for visualisation:\
``` roslaunch ackermann_vehicle_description rviz.launch ```\
Remember to add the odometry topic 

# Topics recorded:
/ackermann_cmd\
/cone_marker_array\
/laps\
/odom\
/path\
/chequered_flag\
/brake\
/emergency_brake
