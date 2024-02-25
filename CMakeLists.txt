cmake_minimum_required(VERSION 3.16.3)
project(git_practice)
add_executable(git_practice main.cpp)
target_compile_options(git_practice PRIVATE -std=c++17 -g -Wall -ggdb3)