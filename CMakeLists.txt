cmake_minimum_required(VERSION 3.28.2)

project(cmake-example-basic)

set(CMAKE_C_STANDARD 11)
set(CMAKE_COMPILE_WARNING_AS_ERROR ON)

add_subdirectory(src)
