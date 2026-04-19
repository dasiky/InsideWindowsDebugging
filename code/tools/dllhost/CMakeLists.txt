add_executable(dllhost main.cpp)
set_target_properties(dllhost PROPERTIES OUTPUT_NAME "host")
target_link_libraries(dllhost PRIVATE corelib kernel32)
