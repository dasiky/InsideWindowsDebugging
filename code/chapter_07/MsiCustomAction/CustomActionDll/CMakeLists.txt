add_library(CustomActionDll SHARED main.cpp customactiondll.def)
target_link_libraries(CustomActionDll PRIVATE corelib kernel32 advapi32 msi)
