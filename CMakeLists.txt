cmake_minimum_required(VERSION 3.27)
project(lab_OOP_7)

set(CMAKE_CXX_STANDARD 17)

include_directories(include)
add_executable(lab_OOP_7
        src/main.cpp
        src/NPC.cpp
        src/Squirrel.cpp
        src/Game.cpp
        src/Knight.cpp
        src/Factory.cpp
        src/FileObserver.cpp
        src/Pegasus.cpp
        src/ConsoleObserver.cpp
)