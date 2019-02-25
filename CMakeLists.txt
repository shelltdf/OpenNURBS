
PROJECT(OpenNURBS)
SET(PROJECT_NAME OpenNURBS)

cmake_minimum_required(VERSION 3.11)

find_package(zlib)
find_package(OpenGL)

OPTION(BUILD_STATIC_LIBRAY "BUILD_STATIC_LIBRAY" ON)

SET(CMAKE_DEBUG_POSTFIX d)

add_subdirectory(src)
add_subdirectory(example_convert)


    

