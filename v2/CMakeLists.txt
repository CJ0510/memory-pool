cmake_minimum_required(VERSION 3.0)
project(v1)

# 头文件
include_directories(${PROJECT_SOURCE_DIR}/include)

aux_source_directory(${PROJECT_SOURCE_DIR}/src DIR_SRCS)

add_executable(v2 main.cpp ${DIR_SRCS})