add_library(ch09_DllLifetimeFix SHARED test.cpp test.def)
set_target_properties(ch09_DllLifetimeFix PROPERTIES OUTPUT_NAME "DllLifetimeFix")
target_link_libraries(ch09_DllLifetimeFix PRIVATE corelib kernel32 advapi32)
