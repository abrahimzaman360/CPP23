cmake_minimum_required(VERSION 3.23)
project(cargorox)

set(CMAKE_CXX_STANDARD 23)

add_executable(cargorox main.cpp include/cargorox.hpp src/cargorox.cpp)
