add_executable(LoggingApp main.cpp)
target_link_libraries(LoggingApp PRIVATE corelib kernel32 advapi32 oleaut32 user32)
