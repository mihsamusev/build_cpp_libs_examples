cmake_minimum_required(VERSION 3.16)
project(boost_example)

# Incude boost
find_package(Boost REQUIRED)
include_directories(${Boost_INCLUDE_DIR})

add_executable(main main.cpp)
target_link_libraries(main ${Boost_LIBRARIES})