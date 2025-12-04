cmake_minimum_required(VERSION 3.20)
project(GLAD LANGUAGES C)

add_library(
    GLAD 
    STATIC
    src/glad.c
)

target_include_directories(
    GLAD 
    PUBLIC 
    "${CMAKE_CURRENT_SOURCE_DIR}/include"
)