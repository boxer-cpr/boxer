cmake_minimum_required(VERSION 2.8.3)
project(boxer_navigation)

find_package(catkin REQUIRED COMPONENTS)

catkin_package(
#  INCLUDE_DIRS include
#  LIBRARIES boxer_navigation
#  CATKIN_DEPENDS amcl gmapping map_server move_base urdf xacro
#  DEPENDS system_lib
)

include_directories(
# include
  ${catkin_INCLUDE_DIRS}
)

install(
  DIRECTORY launch params maps
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)
