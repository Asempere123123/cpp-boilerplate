cmake_minimum_required(VERSION 3.10)

project(MyProject VERSION 0.1)
set(CMAKE_CXX_STANDARD 17)

file(GLOB SOURCES "src/*.cpp")
include_directories(include)
add_executable(MyProject ${SOURCES})
