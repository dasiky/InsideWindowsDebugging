add_executable(ch09_ExeGlobalsLifetime bug.cpp stdafx.h)
set_target_properties(ch09_ExeGlobalsLifetime PROPERTIES OUTPUT_NAME "bug")
target_link_libraries(ch09_ExeGlobalsLifetime PRIVATE corelib kernel32 advapi32)
