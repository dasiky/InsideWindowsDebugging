add_executable(ch09_MultiLockDeadlock main.cpp stdafx.h critsec.h)
set_target_properties(ch09_MultiLockDeadlock PROPERTIES OUTPUT_NAME "bug")
target_link_libraries(ch09_MultiLockDeadlock PRIVATE corelib kernel32 advapi32)
