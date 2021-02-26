cmake_minimum_required(VERSION 3.10.2)
project(poo2_unit5_week8_2021_0_exercise)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_CURRENT_BINARY_DIR}/${OUTPUT_DEBUG})
if(UNIX AND NOT APPLE)
    set(CMAKE_CXX_FLAGS -pthread)
endif()

add_executable(poo2_unit5_week8_2021_0_exercise
  main.cpp 
  p1.h p1.cpp
  p2.h p2.cpp
  p3.h p3.cpp
  p4.h p4.cpp
  p5.h p5.cpp
  p6.h p6.cpp
  p7.h p7.cpp
  p8.h p8.cpp
  p9.h p9.cpp
  p10.h p10.cpp
  )