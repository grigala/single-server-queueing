cmake_minimum_required(VERSION 3.15)
project(single_server_queueing C)

set(CMAKE_C_STANDARD 11)

add_executable(single_server_queueing server.c)