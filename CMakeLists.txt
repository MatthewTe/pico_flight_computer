cmake_minimum_required(VERSION 3.12)

include(src/Libraries/pico-sdk/external/pico_sdk_import.cmake)
project(PicoFC C CXX ASM)

pico_sdk_init()

SET(ENV{PICO_SDK_PATH}, "/Users/matthewteelucksingh/Repos/pico_flight_computer/src/Libraries/pico-sdk")

add_subdirectory(src)