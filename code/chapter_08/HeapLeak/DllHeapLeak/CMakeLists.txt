add_library(ch08_DllHeapLeak SHARED heapleak.cpp heapleak.def)
set_target_properties(ch08_DllHeapLeak PROPERTIES OUTPUT_NAME "HeapLeak")
target_link_libraries(ch08_DllHeapLeak PRIVATE corelib kernel32 advapi32)
