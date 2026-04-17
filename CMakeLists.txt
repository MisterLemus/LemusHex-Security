cmake_minimum_required(VERSION 3.20)

project(LemusHexSecurity VERSION 1.0 LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(LemusHexSecurity
    src/main.cpp
)

target_include_directories(LemusHexSecurity PRIVATE include)
