cmake_minimum_required(VERSION 3.23)
project(C_learning)

set(CMAKE_CXX_STANDARD 14)

include_directories(Array)

add_executable(C_learning
        Array/one_add.cpp
        Array/one_add.h)
