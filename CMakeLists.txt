cmake_minimum_required(VERSION 3.3)
project(parallel_bitonic_sorter)
file(GLOB all_files "*.c")
SET(SOURCE_FILES mpi_bitonic.c)
ADD_EXECUTABLE(${PROJECT_NAME} ${SOURCE_FILES})
