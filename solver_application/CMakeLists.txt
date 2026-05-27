cmake_minimum_required(VERSION 3.10)
project(solver)

add_executable(equation equation.cpp)

target_link_libraries(equation PRIVATE formatter_ex solver)
