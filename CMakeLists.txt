cmake_minimum_required(VERSION 3.23)
project(TinyANN)

set(CMAKE_CXX_STANDARD 17)

include_directories(include)
aux_source_directory(src SRCLIST)

add_executable(TinyANN main.cpp
        ${SRCLIST})
