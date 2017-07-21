cmake_minimum_required(VERSION 3.8)
project(BehaviorPlanner)

set(CMAKE_CXX_STANDARD 14)

set(SOURCE_FILES main.cpp vehicle.cpp vehicle.h road.cpp road.h)
add_executable(BehaviorPlanner ${SOURCE_FILES} vehicle.cpp vehicle.h road.cpp road.h)