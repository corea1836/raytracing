cmake_minimum_required(VERSION 4.4)
project(cudaStart CUDA)

set(CMAKE_CUDA_STANDARD 20)
add_executable(cudaStart main.cu)

set_target_properties(cudaStart PROPERTIES
        CUDA_SEPARABLE_COMPILATION ON)
