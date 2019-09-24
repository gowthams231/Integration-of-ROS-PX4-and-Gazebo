# Integration-of-ROS-PX4-and-Gazebo

Step 1:
Turn on master core
$ roscore

Step 2:
Connect PX4

Step 3:
Connect ROS to px4 using MAVROS using the following command and make sure GPS signal is connected 
$roslaunch mavros px4.launch

Step 4:
Open gazebo model
$src$Firmware$ make px4_sitl gazebo 

Step 5:
source setup.bash in devel folder and run the code 
$rosrun package-name node
