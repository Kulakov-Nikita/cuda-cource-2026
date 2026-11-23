cmake_minimum_required(VERSION 3.20)

project(lab1 LANGUAGES CXX CUDA)

add_executable(submission src/main.cu)

set_target_properties(submission PROPERTIES
    CXX_STANDARD 17
    CXX_STANDARD_REQUIRED ON
    CUDA_STANDARD 17
    CUDA_STANDARD_REQUIRED ON
)
