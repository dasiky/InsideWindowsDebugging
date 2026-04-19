add_library(ch09_DllLifetimeBug SHARED test.cpp test.def)
set_target_properties(ch09_DllLifetimeBug PROPERTIES OUTPUT_NAME "DllLifetimeBug")
target_link_libraries(ch09_DllLifetimeBug PRIVATE corelib kernel32 advapi32)
