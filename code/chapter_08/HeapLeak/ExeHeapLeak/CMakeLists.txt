add_executable(ch08_ExeHeapLeak main.cpp stdafx.h)
set_target_properties(ch08_ExeHeapLeak PROPERTIES OUTPUT_NAME "host")
target_link_libraries(ch08_ExeHeapLeak PRIVATE corelib kernel32)
