add_library(DllModule SHARED main.cpp main.def)
target_link_libraries(DllModule PRIVATE corelib kernel32 advapi32)
