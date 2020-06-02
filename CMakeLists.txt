cmake_minimum_required(VERSION 2.8.12)

set(TARGET_NAME imgui)

project(${TARGET_NAME})

add_compile_options(/MP)

add_library(${TARGET_NAME} STATIC
    imgui.cpp
    imgui_demo.cpp
    imgui_draw.cpp
    imgui_widgets.cpp
)