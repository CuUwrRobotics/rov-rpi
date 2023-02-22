cmake_minimum_required(VERSION 3.0.2)
project(camera_driver)

find_package(catkin REQUIRED COMPONENTS
  libuvc_camera
)

catkin_package(
#  INCLUDE_DIRS include
#  LIBRARIES camera_driver
#  CATKIN_DEPENDS libuvc_camera
#  DEPENDS system_lib
)

###########
## Build ##
###########

## Specify additional locations of header files
## Your package locations should be listed before other locations
include_directories(
# include
  ${catkin_INCLUDE_DIRS}
)
