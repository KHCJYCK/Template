cmake_minimum_required(VERSION 3.0)

project(TEMPLATE)
add_subdirectory(src)
include_directories(include)

add_executable(main main.cpp)
target_link_libraries(main srclib)