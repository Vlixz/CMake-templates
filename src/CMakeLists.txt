add_executable(print main.c print.c)

target_include_directories(print PUBLIC ${CMAKE_SOURCE_DIR}/include)
