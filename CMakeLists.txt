cmake_minimum_required(VERSION 3.12)
project(Fraction)

set(CMAKE_CXX_STANDARD 11)

add_executable(Fraction src/main.cc src/fraction.cc)
include_directories(include)