cmake_minimum_required(VERSION 3.7)
project(PhaseDetector)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        Makefile
        OpenEphysLib.cpp
        PhaseDetector.cpp
        PhaseDetector.h
        PhaseDetectorEditor.cpp
        PhaseDetectorEditor.h)

add_executable(PhaseDetector ${SOURCE_FILES})