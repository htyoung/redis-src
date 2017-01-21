cmake_minimum_required(VERSION 3.6)
project(redis_src)

set(CMAKE_C_STANDARD 11)

set(SOURCE_FILES main.c)
add_executable(redis_src ${SOURCE_FILES})