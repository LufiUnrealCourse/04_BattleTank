cmake_minimum_required(VERSION 3.15)
project(Source)

set(CMAKE_CXX_STANDARD 14)

include_directories(BattleTank)

add_executable(Source
        BattleTank/BattleTank.cpp
        BattleTank/BattleTank.h
        BattleTank/BattleTankGameModeBase.cpp
        BattleTank/BattleTankGameModeBase.h)
