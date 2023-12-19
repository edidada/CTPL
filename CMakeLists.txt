cmake_minimum_required(VERSION 3.14)
project(CTPL_example)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(CTPL
        ctpl.h
        ctpl_stl.h
        example.cpp)
