cmake_minimum_required(VERSION 3.10)
project(ffserver C)

set(CMAKE_C_STANDARD 99)

add_executable(ffserver src/main.c)