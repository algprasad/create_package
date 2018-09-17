# create_package

This script file will perform the steps necessary to build a ros package. 

Go to the catkin workspace and run this script there. (You dont have to put the script there, just call it from inside the workspace)

The arguments being the name of the package and it dependencies. (Please note that the dependencies of roscpp rospy and std_msgs have already been included, so no need to include them)
On running the script, the source file will be created and the corresponding CMakeLists.txt will be updated with the name of the source file in the add_executable() function. 

Sample run: 

cd ~/catkin_ws

sh ~/createpack.sh name_of_package geometry_msgs sensor_msgs
