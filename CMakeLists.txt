cmake_minimum_required(VERSION 3.9)
project(tiny_sha3 C CXX)

set(CMAKE_CXX_STANDARD 17)

file(GLOB SOURCES
        "*.h"
        "*.c")

add_executable(sha3test ${SOURCES})
