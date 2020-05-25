cmake_minimum_required(VERSION 3.16.2)

add_executable(CMakeTest src/main.cpp)

enable_testing()
add_subdirectory("tests")