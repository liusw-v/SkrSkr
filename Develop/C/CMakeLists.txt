# cmake_minimum_required(VERSION 3.10.2)
project(SkyNet)

set(CMAKE_CXX_STANDARD 14)
SET(CMAKE_BUILD_TYPE "Release")

add_executable(SkyNet src/main.cpp src/SkyNet.cpp src/utils.cpp src/transform.cpp)
target_include_directories(SkyNet
    PRIVATE 
        /home/lsw/tools/Xilinx/Vivado/2020.2/include
)