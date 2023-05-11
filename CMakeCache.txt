cmake_minimum_required(VERSION 3.9.1)

project("chip8")

#add_subdirectory(src)
include_directories(include)

file(GLOB MAIN
    "src/.cpp"
    "include/.h"
)
add_executable("${PROJECT_NAME}" "${MAIN}")