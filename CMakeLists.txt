cmake_minimum_required(VERSION 3.8)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_BUILD_TYPE DEBUG)

project(Encryption)

file(GLOB src src/*.cpp)
add_executable(Encryption.out ${src})