
cmake_minimum_required(VERSION 3.10)
project(solver)
add_executable(equation equation.cpp)
target_include_directories(equation PRIVATE ${CMAKE_CURRENT_SOURCE_DIR}/../formatter_ex_lib ${CMAKE_CURRENT_SOURCE_DIR}/../solver_lib)
target_link_libraries(equation PRIVATE formatter_ex solver)
