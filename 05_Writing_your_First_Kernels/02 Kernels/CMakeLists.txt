cmake_minimum_required(VERSION 3.10)

project(02_kernels CUDA)

add_executable(00_vector_add_v1 00_vector_add_v1.cu)
add_executable(01_vector_add_v2 01_vector_add_v2.cu)
add_executable(02_matmul 02_matmul.cu)

