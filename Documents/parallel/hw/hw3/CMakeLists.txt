cmake_minimum_required(VERSION 3.13)
project(hw3)

set(CMAKE_CXX_STANDARD 14)

add_executable(hw3
    cmake-build-debug/cmake_install.cmake
    cmake-build-debug/CMakeCache.txt
    cmake-build-debug/hw3
    cmake-build-debug/hw3.cbp
    cmake-build-debug/makefile
    CMakeLists.txt
    makefile
    parcount
    parcount.cpp
    parcount.o)
