cmake_minimum_required(VERSION 3.4)

project(
    ThreadPool
    VERSION 1.0
    DESCRIPTION "C++ Threadpool"
    LANGUAGES CXX
)

add_library(ThreadPool::ThreadPool INTERFACE)
target_include_directories(ThreadPool::ThreadPool INTERFACE include/)