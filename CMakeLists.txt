cmake_minimum_required(VERSION 3.27)
project(untitled1)

set(CMAKE_CXX_STANDARD 17)

add_library(untitled1 STATIC library.cpp)

add_executable(main main.cpp)

target_link_libraries(main.cpp library.cpp)
