set (TEST_STAG_H
    )

set (TEST_STAG_C
    test.c
    )

link_directories(${CMAKE_BINARY_DIR}/src)
include_directories(${CMAKE_BINARY_DIR}/src)

add_executable(stag_test ${TEST_STAG_C})
target_link_libraries(stag_test stag)

