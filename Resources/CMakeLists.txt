cmake_minimum_required(VERSION 3.16)
project(Cellular_Automats)

SET(CMAKE_CXX_STANDARD 11)

add_library(Cellular_Automats Cellular_Automats.cpp Cellular_Automats.h)
target_include_directories(Cellular_Automats PUBLIC .)

