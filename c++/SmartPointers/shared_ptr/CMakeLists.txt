cmake_minimum_required(VERSION 2.6)

PROJECT(shared_ptr)

SET(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall -std=gnu++0x")

ADD_EXECUTABLE(shared_ptr shared_ptr.cpp)

ADD_EXECUTABLE(Abstract Abstract.cpp)
