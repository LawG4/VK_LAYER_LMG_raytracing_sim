cmake_minimum_required(VERSION 3.0.0 FATAL_ERROR)
set(LAYER_NAME "VK_LAYER_LMG_raytracing_sim")

# Add a top level project and library for the layer
project(${LAYER_NAME} VERSION 0.1.0 LANGUAGES C)
add_library("${LAYER_NAME}" SHARED Source/Main.c)