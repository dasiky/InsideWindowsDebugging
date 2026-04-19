cmake_minimum_required(VERSION 3.15)
project(InsideWindowsDebugging LANGUAGES CXX C)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# 公共编译定义
add_compile_definitions(UNICODE _UNICODE)

# MSVC特定设置
if(MSVC)
    add_compile_options(/W3 /MP)
    # 支持Debug/Release
    set(CMAKE_MSVC_RUNTIME_LIBRARY "MultiThreadedDebugDLL" CACHE STRING "")
endif()

# 公共库
add_subdirectory(common/corelib)

# 各章节
add_subdirectory(chapter_01)
add_subdirectory(chapter_02)
add_subdirectory(chapter_03)
add_subdirectory(chapter_04)
add_subdirectory(chapter_05)
add_subdirectory(chapter_06)
add_subdirectory(chapter_07)
add_subdirectory(chapter_08)
add_subdirectory(chapter_09)
add_subdirectory(chapter_10)
add_subdirectory(chapter_12)
add_subdirectory(chapter_13)
add_subdirectory(tools)
