add_executable(stlsample main.cpp stdafx.h)
target_link_libraries(stlsample PRIVATE corelib kernel32 advapi32)
target_compile_options(stlsample PRIVATE /EHsc)
