cmake_minimum_required(VERSION 3.28)
project(basic_cpp_catch
        VERSION 0.1.0
        DESCRIPTION "Basic C++ project with Catch2 unit tests"
        LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 20)

add_executable(basic_cpp_catch main.cpp)