cmake_minimum_required(VERSION 3.3.2)
project(UltraLight C CXX)

include(cmake/App.cmake)

set(SOURCES "native/NativeApp.h"
            "native/NativeApp.cpp"
            "native/main.cpp")

add_app("${SOURCES}")