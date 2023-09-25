cmake_minimum_required(VERSION 3.26)
project(mix_rPBR C)

set(CMAKE_C_STANDARD 17)
find_package(raylib REQUIRED)

include_directories(libs)

add_executable(mix_rPBR src/rpbr.c)
target_link_libraries(${PROJECT_NAME} raylib)
