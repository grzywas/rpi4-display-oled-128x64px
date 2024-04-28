cmake_minimum_required(VERSION 3.10)
project(rpi4-display-oled-128x64px)

set(CMAKE_ARCHIVE_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR})
set(CMAKE_LIBRARY_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR})
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR})

add_executable(rpi4-display-oled-128x64px rpi4-display-oled-128x64px.c)
