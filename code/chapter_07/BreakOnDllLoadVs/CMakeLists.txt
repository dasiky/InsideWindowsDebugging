add_executable(BreakOnDllLoadVs host.cpp)
target_link_libraries(BreakOnDllLoadVs PRIVATE corelib kernel32)
