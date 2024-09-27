cmake_minimum_required(VERSION 3.29)
project(Loop C)

set(CMAKE_C_STANDARD 17)

add_subdirectory(1-types-io)
add_executable(CMakeLists 1-types-io/CMakeLists.txt)
add_executable(circle 1-types-io/circle.c)