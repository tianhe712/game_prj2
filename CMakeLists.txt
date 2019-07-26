cmake_minimum_required(VERSION 3.10)
project(game_prj2)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(game_prj2
        game_channel.cpp
        game_channel.h
        game_protocol.cpp
        game_protocol.h
        game_role.cpp
        game_role.h
        GameMsg.cpp
        GameMsg.h
        main.cpp)
