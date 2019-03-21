
PROJECT(OpenNURBS)
SET(PROJECT_NAME OpenNURBS)

cmake_minimum_required(VERSION 3.11)

find_package(zlib)
find_package(OpenGL)

OPTION(BUILD_STATIC_LIBRAY "BUILD_STATIC_LIBRAY" OFF)

SET(CMAKE_DEBUG_POSTFIX d)

add_subdirectory(src)
add_subdirectory(example_convert)
add_subdirectory(example_brep)
# add_subdirectory(example_gl)
add_subdirectory(example_read)
add_subdirectory(example_roundtrip)
add_subdirectory(example_test)
add_subdirectory(example_userdata)
add_subdirectory(example_write)


    

