
cmake_minimum_required(VERSION 2.8.3)
project(robotnik_sensors)

find_package(catkin REQUIRED COMPONENTS gazebo_plugins hector_gazebo_plugins)

catkin_package()

install(
  DIRECTORY meshes urdf
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)
