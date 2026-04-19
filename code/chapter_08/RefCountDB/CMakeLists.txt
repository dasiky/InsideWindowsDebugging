add_executable(ch08_RefCountDB main.cpp stdafx.h reftracker.h)
target_link_libraries(ch08_RefCountDB PRIVATE corelib kernel32 advapi32)
