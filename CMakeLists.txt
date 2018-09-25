cmake_minimum_required(VERSION 2.6)
project(SAMSENGINE)

add_executable(sandbox
	src/main.cpp
)

add_library(engine
	src/engine/engineentitty.cpp
)