cmake_minimum_required(VERSION 3.10)
project(glad)
add_library(glad release/src/glad.c)
target_include_directories(glad PUBLIC release/include)
