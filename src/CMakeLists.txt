cmake_minimum_required(VERSION 3.21)
project(src)

set(CMAKE_CXX_STANDARD 14)

add_executable(src
        board.cpp
        game.cpp
        main.cpp)
