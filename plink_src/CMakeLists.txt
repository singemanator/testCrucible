cmake_minimum_required(VERSION 3.2)
project(plink_src)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

add_custom_target(plink_src COMMAND make -C ${plink_src_SOURCE_DIR}
                         CLION_EXE_DIR=${PROJECT_BINARY_DIR})