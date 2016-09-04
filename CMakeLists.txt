cmake_minimum_required(VERSION 3.5)
project(6771_tut_week8)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++14 -Wall -Werror -g")

set(SOURCE_FILES week8.cpp Library.h)
add_executable(6771_tut_week8 ${SOURCE_FILES})