cmake_minimum_required(VERSION 3.9)
project(OpenCV_testc)

# Find OpenCV package
find_package(OpenCV REQUIRED)

# Include directories from OpenCV
include_directories(${OpenCV_INCLUDE_DIRS})

# Create an executable
add_executable(OpenCV_testc main.cpp)

# Link OpenCV libraries
target_link_libraries(OpenCV_testc ${OpenCV_LIBS})