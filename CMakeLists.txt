cmake_minimum_required(VERSION 2.8.4)
project(x264)

add_custom_target(x264 COMMAND make -C ${PROJECT_SOURCE_DIR} CLION_EXE_DIR=${PROJECT_BINARY_DIR})