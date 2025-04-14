cmake_minimum_required(VERSION 3.28)
project(Btree)

set(CMAKE_CXX_STANDARD 17)

add_executable(Btree main.cpp
        BTreeIndex.h
        BTreeIndex.cpp)
