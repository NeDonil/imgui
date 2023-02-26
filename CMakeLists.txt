cmake_minimum_required(VERSION 3.21)
project(imgui)

set(CMAKE_CXX_STANDARD 14)

add_library(imgui
    imconfig.h
    imgui.h
    imgui.cpp
    imgui_draw.cpp
    imgui_internal.h
    imgui_tables.cpp
    imgui_widgets.cpp
    imstb_rectpack.h
    imstb_textedit.h
    imstb_truetype.h
    imgui_demo.cpp
)
