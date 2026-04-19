add_executable(ch09_DllLifetimeHost main.cpp stdafx.h)
set_target_properties(ch09_DllLifetimeHost PROPERTIES OUTPUT_NAME "DllLifetimeHost")
target_link_libraries(ch09_DllLifetimeHost PRIVATE corelib kernel32 advapi32)
