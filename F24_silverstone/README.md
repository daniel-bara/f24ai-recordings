Here you will find rosbag recorded during the F24 Silverstone event.

/tf was not recorded, so /odom does not relate to /world. To visualise the odometry and other topics on the same screen, use the following:\
``` rosrun tf2_ros static_transform_publisher 0 0 0 0 0 0 /world /odom ```
# Topics recorded:
/ackermann_cmd\
/cone_marker_array\
/laps\
/odom\
/path
