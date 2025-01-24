cmake_minimum_required(VERSION 3.5)

project(opengl)

if(MSVC)
  set(CMAKE_EXE_LINKER_FLAGS /NODEFAULTLIB:"MSVCRT")
endif()

set(CMAKE_BUILD_TYPE "Debug")

add_executable(main main2.cpp)
