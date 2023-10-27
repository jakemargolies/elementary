# TODO 1: Set the minimum required version of CMake to be 3.10
cmake_minimum_required(VERSION 3.10)
# TODO 2: Create a project named Tutorial
project(Elementary)
# TODO 7: Set the project version number
# TODO 6: Set the variable CMAKE_CXX_STANDARD to 11
#         and the variable CMAKE_CXX_STANDARD_REQUIRED to True

add_executable(Elementary elementary.cpp)
# TODO 9: Use target_include_directories to include ${PROJECT_BINARY_DIR}
