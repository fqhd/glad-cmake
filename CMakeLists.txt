cmake_minimum_required(VERSION 3.15.0)
project(glad-cmake VERSION 1.0.0)

add_library(glad-cmake src/glad.c)

target_include_directories(glad-cmake PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/include)
