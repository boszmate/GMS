cmake_minimum_required(VERSION 3.14)
project(3)

set(CMAKE_CXX_STANDARD 14)

add_executable(3 main.cpp hpp/FileReader.hpp cpp/FileReader.cpp)