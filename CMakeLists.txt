cmake_minimum_required(VERSION 3.15)
project(lua C)

option(USE_LUA_DEFINITIONS "Whether or not to use pthreads, etc." ON)

message(STATUS "USE_LUA_DEFINITIONS: ${USE_LUA_DEFINITIONS}")

add_subdirectory(lua-5.3.3)   
