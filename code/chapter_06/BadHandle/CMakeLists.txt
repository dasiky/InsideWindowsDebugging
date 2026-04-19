add_executable(BadHandleBug main.cpp)
target_link_libraries(BadHandleBug PRIVATE corelib kernel32 advapi32)
