cmake_minimum_required(VERSION 3.0.0 FATAL_ERROR)

project(hello CXX)

set(LIB_SRCS
    src/hello.cpp
)

add_executable(${PROJECT_NAME}_example ${SAMPLE_SRC})

set_property(TARGET ${PROJECT_NAME} PROPERTY CXX_STANDARD 14)

