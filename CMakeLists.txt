cmake_minimum_required(VERSION 3.12)
project(test)

set(CMAKE_CXX_STANDARD 17)

add_executable(test main.cpp Arguments.cpp Statistics.cpp Operation.cpp FileOperationFactory.cpp FileOperationFactory.h)