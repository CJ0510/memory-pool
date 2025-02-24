cmake_minimum_required(VERSION 3.0)
project(memorypool)

set(CMAKE_BUILD_TYPE "Debug")
set(CMAKE_CXX_FLAGS ${CMAKE_CXX_FLAGS} -g)
# 设置cmake全局变量
set(EXECUTABLE_OUTPUT_PATH ${PROJECT_SOURCE_DIR}/bin)

add_subdirectory(v1)
add_subdirectory(v2)