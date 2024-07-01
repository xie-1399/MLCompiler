# here is whole mlc project cmake list

cmake_minimum_required(VERSION 3.19)
project(mlc)
set(CMAKE_CXX_STANDARD 14)

add_subdirectory(framework)
add_subdirectory(compiler)

add_executable(main main.cc)
