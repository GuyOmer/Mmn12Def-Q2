cmake_minimum_required(VERSION 3.16)
project(q2)

set(CMAKE_CXX_STANDARD 11)

add_executable(q2 main.cpp)
set_target_properties(q2 PROPERTIES COMPILE_FLAGS "-m32" LINK_FLAGS "-m32")