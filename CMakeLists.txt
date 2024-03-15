cmake_minimum_required(VERSION 3.16.0)
include($ENV{IDF_PATH}/tools/cmake/project.cmake)
project(LoRa_Walky)

add_library(MarketLibrary
    src/shared/esp32/radio.cpp
    src/remote/remote.h
    src/remote/remote.cpp
)