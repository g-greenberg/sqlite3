# CMakeList.txt : Top-level CMake project file, do global configuration
# and include sub-projects here.
#
cmake_minimum_required (VERSION 3.8)

project ("sqlite")

add_Library(sqlite3 "sqlite3.c" "shell.c" "sqlite3.h" "sqlite3ext.h")

