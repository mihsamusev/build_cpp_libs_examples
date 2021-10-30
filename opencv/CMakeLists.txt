cmake_minimum_required(VERSION 3.16)
project(opencv_example)

# Incude opencv
set(OpenCV_DIR /home/msa/Documents/repos/opencv/build)
find_package(OpenCV 4 REQUIRED)
include_directories(${OpenCV_INCLUDE_DIRS})

add_executable(main main.cpp)
target_link_libraries(main ${OpenCV_LIBS})
