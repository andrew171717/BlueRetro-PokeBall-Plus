# The following lines of boilerplate have to be in your project's
# CMakeLists in this exact order for cmake to work correctly
cmake_minimum_required(VERSION 3.5)
set(PROJECT_VER "25.04-PBP-r1")

include($ENV{IDF_PATH}/tools/cmake/project.cmake)
project("BlueRetro$ENV{BR_HW}$ENV{BR_SYS}")
