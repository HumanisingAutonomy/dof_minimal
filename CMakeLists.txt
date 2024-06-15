cmake_minimum_required(VERSION 3.23.0)

project(dof_minimal LANGUAGES CXX CUDA)

find_package(OpenCV)

add_executable(main main.cpp)
target_link_libraries(main PUBLIC opencv_highgui)