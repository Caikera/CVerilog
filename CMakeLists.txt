cmake_minimum_required(VERSION 3.23)
project(CVerilog)

set(CMAKE_CXX_STANDARD 20)

include_directories(".")
add_executable(CVerilog src/main.cpp src/reg.h src/data.h src/node.h src/op.h src/module.h src/get_v.h)
add_definitions(-DFMT_HEADER_ONLY)