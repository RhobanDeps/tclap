cmake_minimum_required(VERSION 3.16.3)
project(tclap)

add_library(tclap INTERFACE)
target_include_directories(tclap INTERFACE
 $<BUILD_INTERFACE:${CMAKE_CURRENT_LIST_DIR}/include>
)

