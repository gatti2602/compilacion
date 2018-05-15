cmake_minimum_required(VERSION 2.8)

project(cmake-demo)

FILE(GLOB myFiles "*.cpp")

message (STATUS "Cargué ${myFiles}")

add_executable(ej4 ${myFiles} main.cpp)
