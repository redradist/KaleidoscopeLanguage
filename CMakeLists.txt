cmake_minimum_required(VERSION 3.13)

set(CMAKE_C_COMPILER clang-9)
set(CMAKE_CXX_COMPILER clang++-9)
include_directories(/usr/include/llvm-9
                    /usr/include/llvm-c-9)

project(KaleidoscopeLanguage)

set(CMAKE_CXX_STANDARD 17)

add_executable(KaleidoscopeLanguage main.cpp)