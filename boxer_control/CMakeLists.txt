cmake_minimum_required(VERSION 2.8.3)
project(boxer_control)

find_package(catkin REQUIRED COMPONENTS
  controller_interface
  diff_drive_controller
  nav_msgs
  roscpp
  boxer_msgs
  std_msgs
  diagnostic_updater
)

catkin_package()

include_directories(
  include
  ${catkin_INCLUDE_DIRS}
)

install(DIRECTORY launch config
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)
