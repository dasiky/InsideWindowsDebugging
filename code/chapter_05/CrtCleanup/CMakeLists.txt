add_executable(crtcleanup main.cpp stdafx.h)
target_link_libraries(crtcleanup PRIVATE corelib kernel32 advapi32)
