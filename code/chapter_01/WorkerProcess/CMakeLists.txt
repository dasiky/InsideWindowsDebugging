add_executable(workerprocess main.cpp stdafx.h)
target_link_libraries(workerprocess PRIVATE corelib kernel32 advapi32 oleaut32 user32)
