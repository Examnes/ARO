cmake_minimum_required(VERSION 3.8 FATAL_ERROR)
project(ARO VERSION 1.0 LANGUAGES CXX)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -O2 -Wall -Wextra -std=c++11")

target_sources(${CMAKE_PROJECT_NAME}

set(SRC ${PROJECT_SOURCE_DIR}/main.cpp

)

add_executable(${CMAKE_PROJECT_NAME} ${SRC})
target_include_directories(${CMAKE_PROJECT_NAME} PUBLIC ${PROJECT_SOURCE_DIR}/include)

