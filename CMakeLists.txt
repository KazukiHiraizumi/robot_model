cmake_minimum_required(VERSION 2.8.3)
project(robot_model)
# Load catkin and all dependencies required for this package
find_package(catkin REQUIRED)
catkin_package()

install(FILES plugin.xml
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)

install(DIRECTORY resource
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)

install(PROGRAMS scripts/rqt_publisher
  DESTINATION ${CATKIN_PACKAGE_BIN_DESTINATION}
)
