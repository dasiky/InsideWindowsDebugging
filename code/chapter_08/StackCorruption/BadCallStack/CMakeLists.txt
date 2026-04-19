add_executable(ch08_BadCallStack main.cpp stdafx.h)
set_target_properties(ch08_BadCallStack PROPERTIES OUTPUT_NAME "BadCallStack")
target_link_libraries(ch08_BadCallStack PRIVATE corelib kernel32)
