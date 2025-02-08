cmake_minimum_required(VERSION 3.22)
project(ec2b)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(ec2b
        aes.c
        magic.h
        main.cpp
        util.c
        util.h
)
