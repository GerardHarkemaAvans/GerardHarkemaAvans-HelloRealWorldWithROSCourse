cmake_minimum_required(VERSION 2.8.3)

project(hrwros_utilities)

## Find catkin macros and libraries
## if COMPONENTS list like find_package(catkin REQUIRED COMPONENTS xyz)
## is used, also find other catkin packages
find_package(catkin REQUIRED COMPONENTS
  rospy
  std_msgs
  hrwros_msgs
)

catkin_package()


