cmake_minimum_required(VERSION 2.8)
project(main)

#c++23
set(CMAKE_CXX_STANDARD 23)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS}  -Wall -Wextra -Werror -pedantic")

set(SOURCE_FILES
        src/main.cpp
)

add_executable(main ${SOURCE_FILES})