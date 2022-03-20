cmake_minimum_required(VERSION 2.8)
project(C4_HW)

set(CMAKE_BUILD_TYPE "Release")
set(CMAKE_CXX_FLAGS "-O3")

include_directories("/usr/include/eigen3")

include_directories(${PROJECT_SOURCE_DIR}/include)
add_subdirectory(src)
add_subdirectory(app)