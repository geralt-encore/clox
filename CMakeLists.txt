cmake_minimum_required(VERSION 3.15)

project(clox)

set(EXECUTABLE_OUTPUT_PATH ${CMAKE_SOURCE_DIR}/bin)

add_executable(clox
  main.c
  chunk.c
  memory.c
  debug.c
  value.c
  vm.c
  compiler.c
  scanner.c
)