cmake_minimum_required(VERSION 3.21)
project(cerberus_slam)

find_package(ament_cmake REQUIRED)

install(DIRECTORY launch config
   DESTINATION share/${PROJECT_NAME}
)

ament_package()
