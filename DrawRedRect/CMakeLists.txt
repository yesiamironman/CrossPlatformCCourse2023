cmake_minimum_required(VERSION 3.25)
project(DrawRedRect C)

set(CMAKE_C_STANDARD 11)

link_libraries(SDL2)

add_executable(DrawRedRect main.c)
