cmake_minimum_required(VERSION 3.1)
project(lua C)
add_subdirectory(lua-5.3.3)    

option(USE_LUA_DEFINITIONS "Whether or not to use pthreads, etc." ON)
