cmake_minimum_required(VERSION 3.5)

project(singleton VERSION 0.1 LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(singleton
    main.cpp
    singleton.cpp
)