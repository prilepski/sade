cmake_minimum_required(VERSION 2.8.2)

project(sade C CXX)

set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_HOME_DIRECTORY}/build)

include_directories(${CMAKE_HOME_DIRECTORY}/include)

file(GLOB sade_src "*.h" "*.cpp")
add_executable(sade ${sade_src})
