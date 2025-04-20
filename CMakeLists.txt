cmake_minimum_required(VERSION 3.29.3)
project(cmake_test CXX)

set(srcs
    ./src/main.cpp
)

add_executable(main ${srcs})
include_directories(include)