add_executable(NTHeapMemory main.cpp)
set_target_properties(NTHeapMemory PROPERTIES OUTPUT_NAME "leak")
target_link_libraries(NTHeapMemory PRIVATE corelib kernel32 advapi32)
