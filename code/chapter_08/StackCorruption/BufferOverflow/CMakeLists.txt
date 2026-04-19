add_executable(ch08_BufferOverflow main.cpp stdafx.h)
set_target_properties(ch08_BufferOverflow PROPERTIES OUTPUT_NAME "StackCorruption")
target_link_libraries(ch08_BufferOverflow PRIVATE corelib kernel32)
