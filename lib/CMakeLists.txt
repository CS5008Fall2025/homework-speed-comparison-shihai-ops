cmake_minimum_required(VERSION 4.0)
project(lib C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(lib
        bst.c
        bst.h
        linked_list.c
        linked_list.h
        movie.c
        movie.h
        sorted_list.c
        sorted_vector.c
        vector.c
        vector.h)
