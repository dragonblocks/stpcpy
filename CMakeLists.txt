cmake_minimum_required(VERSION 3.14)
project(Stpcpy)

add_compile_options(
	-Wall
	-Wextra
	-Werror
)

add_library(stpcpy
	stpcpy.c
)

target_include_directories(stpcpy
	PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}
)
