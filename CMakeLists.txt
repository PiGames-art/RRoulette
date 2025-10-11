# Vibe coded cmake bcz i don't know it and dont want to deal with it.
# Russian Roulette
cmake_minimum_required(VERSION 3.10)
project(rroulette)

set(CMAKE_CXX_STANDARD 17)
include_directories(include)

file(GLOB SRC "src/*.cpp" "src/*.c")
add_executable(rroulette ${SRC})
