add_executable(ServiceWithCrash Main.cpp stdafx.h)
target_link_libraries(ServiceWithCrash PRIVATE corelib kernel32 advapi32)
