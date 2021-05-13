cmake_minimum_required(VERSION 3.17)
project(EchoLands C)

set(CMAKE_C_STANDARD 99)

add_executable(EchoLands Draw.h Entity.h Main.c)
target_link_libraries(EchoLands -lOpenGL32 -lfreeGLUT)