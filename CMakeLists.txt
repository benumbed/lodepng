cmake_minimum_required(VERSION 3.8)
project(lodepng VERSION 20191109 LANGUAGES CXX)

set(CMAKE_CXX_FLAGS "-Wall -Wextra -pedantic -ansi -O3")
add_library(lodepng STATIC lodepng.cpp)