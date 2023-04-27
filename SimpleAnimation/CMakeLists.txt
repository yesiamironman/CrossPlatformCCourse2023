cmake_minimum_required(VERSION 3.25)
project(ModifyPixel C)

set(CMAKE_C_STANDARD 11)

link_libraries(SDL2)

add_executable(ModifyPixel main.c)
