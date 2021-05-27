cmake_minimum_required(VERSION 2.8 FATAL_ERROR)
project(vfs)

set( CMAKE_BUILD_TYPE RelWithDebInfo)
set(OpenCV_DIR "/home/wxm/Documents/download_libs/opencv-4.5.1/build/") # which change to your own path

add_subdirectory(stereotgv)
add_subdirectory(test_vfs)
