cmake_minimum_required(VERSION 3.19)
project(maclura)

set(CMAKE_CXX_STANDARD 17)

add_executable(maclura main.cpp maclura/config.cpp maclura/config.hpp)