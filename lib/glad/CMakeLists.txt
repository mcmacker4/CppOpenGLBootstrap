cmake_minimum_required(VERSION 3.0)
project(GLAD)

add_library(GLAD include/glad/glad.h src/glad.c)
target_include_directories(GLAD PUBLIC include/)