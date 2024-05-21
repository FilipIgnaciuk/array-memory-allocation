cmake_minimum_required(VERSION 3.27)
project(array_memory_allocation)

set(CMAKE_CXX_STANDARD 17)

add_executable(array_memory_allocation main.cpp
        array.cpp
        array.h)
