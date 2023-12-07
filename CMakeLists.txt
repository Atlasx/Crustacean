cmake_minimum_required(VERSION 3.28)

project(Crustacean
	VERSION 0.0
	DESCRIPTION "Game Engine")

add_library(Crustacean STATIC src/main.cpp)

set(CMAKE_CXX_STANDARD 20)