add_executable(BufferOverrunBug main.cpp)
target_link_libraries(BufferOverrunBug PRIVATE corelib kernel32)
