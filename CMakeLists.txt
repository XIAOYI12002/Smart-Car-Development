cmake_minimum_required(VERSION 3.10)
project(SmartCar CXX)

# 设置C++标准
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# 添加可执行文件
add_executable(hello_smartcar src/hello_smartcar.cpp)
