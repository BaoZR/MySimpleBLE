cmake_minimum_required(VERSION 3.21)


include(${CMAKE_CURRENT_SOURCE_DIR}/cmake/prelude.cmake)
project(
    simpleble
    VERSION ${SIMPLEBLE_VERSION}
    DESCRIPTION "The cross-platform library for Bluetooth Low Energy (BLE)."
    HOMEPAGE_URL "https://github.com/OpenBluetoothToolbox/SimpleBLE"
    LANGUAGES CXX
)
# Run prelude script to set up environment
include(${CMAKE_CURRENT_SOURCE_DIR}/cmake/epilogue.cmake)

add_subdirectory(simpleble)

