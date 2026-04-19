add_library(ch09_SingleLockDeadlock SHARED test.cpp test.def)
set_target_properties(ch09_SingleLockDeadlock PROPERTIES OUTPUT_NAME "test")
target_link_libraries(ch09_SingleLockDeadlock PRIVATE corelib kernel32 advapi32)
