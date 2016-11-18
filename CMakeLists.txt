cmake_minimum_required(VERSION 3.6)
project(Enterprise)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES
    tuple_text_to_binary_csr/Makefile
    tuple_text_to_binary_csr/tuple_text_to_bin.cpp
    allocator.cuh
    bfs_gpu_opt.cuh
    comm.h
    expander.cuh
    graph.h
    graph.hpp
    inspector.cuh
    License.txt
    main.cu
    Makefile
    readme.md
    scan.cuh
    validate.h
    write_result.cuh
    wtime.h)

add_executable(Enterprise ${SOURCE_FILES})