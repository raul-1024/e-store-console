cmake_minimum_required(VERSION 3.10)
project(e_store_console)

set(CMAKE_CXX_STANDARD 17)

file(GLOB SOURCES "src/*.cpp")

add_executable(app ${SOURCES})

target_include_directories(app PRIVATE include)
