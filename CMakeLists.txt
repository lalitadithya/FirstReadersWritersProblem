cmake_minimum_required(VERSION 3.6)
project(FirstReadersWritersProblem)

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -std=c11")

set(SOURCE_FILES main.c)
add_executable(FirstReadersWritersProblem ${SOURCE_FILES})
target_link_libraries(FirstReadersWritersProblem pthread)