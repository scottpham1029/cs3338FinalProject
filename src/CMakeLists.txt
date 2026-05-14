cmake_minimum_required(VERSION 3.10)

project(HDR_Dynamic_Tone_Mapping_OpenFX)

# Mock build configuration for planned OpenFX plugin source structure.
# A full implementation would include OpenFX SDK paths, plugin source files,
# compiler settings, and DaVinci Resolve plugin packaging rules.

set(CMAKE_CXX_STANDARD 17)

add_library(HDRToneMappingPlugin SHARED
    PluginEntry.cpp
    ToneMappingEngine.cpp
    LuminanceAnalyzer.cpp
    PresetManager.cpp
    PreviewRenderer.cpp
)
