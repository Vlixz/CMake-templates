cmake_minimum_required(VERSION 3.28.2)

# Name of the project
project(cmake-example-basic)

# C standards
#   - 90 (C89/C90)
#   - 99 (C99)
#   - 11 (C11)
#   - 17 (C17)
#   - 23 (C23)
set(CMAKE_C_STANDARD 11)

set(CMAKE_COMPILE_WARNING_AS_ERROR ON)

add_subdirectory(src)
