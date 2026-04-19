add_executable(ch08_HeapCorruption main.cpp stdafx.h)
set_target_properties(ch08_HeapCorruption PROPERTIES OUTPUT_NAME "OffByOne")
target_link_libraries(ch08_HeapCorruption PRIVATE corelib kernel32)
