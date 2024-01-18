cmake_minimum_required(VERSION 3.27)
project(project)

set(CMAKE_CXX_STANDARD 20)

add_executable(project main.cpp)
add_executable(b test.cpp)
add_executable(c second.cpp)

add_executable(test test.cpp)
add_executable(fifth fifth.cpp)
add_executable(sixth sixth.cpp)