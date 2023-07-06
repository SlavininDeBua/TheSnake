cmake_minimum_required(VERSION 3.12)
include("${CMAKE_CURRENT_SOURCE_DIR}/Configure.cmake")
project(TheSnake)

project(${PROJECT_NAME} C CXX)

set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_subdirectory("${CMAKE_CURRENT_SOURCE_DIR}/3rdparty/SFML")
include_directories("${CMAKE_SOURCE_DIR}/3rdparty/SFML/include")

add_subdirectory(bin)
add_subdirectory(lib)
