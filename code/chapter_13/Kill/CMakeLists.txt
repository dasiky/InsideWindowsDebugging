add_executable(Kill main.cpp)
set_target_properties(Kill PROPERTIES OUTPUT_NAME "kill")
target_link_libraries(Kill PRIVATE corelib kernel32 advapi32)
