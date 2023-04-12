cmake_minimum_required(VERSION 3.10)
project(base64 VERSION 1.0.0 DESCRIPTION "Header-base base64 helper functions")
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_library(${PROJECT_NAME} INTERFACE)
target_include_directories(${PROJECT_NAME} INTERFACE include)
