include_directories(${gtest_SOURCE_DIR}/include ${gtest_SOURCE_DIR})

add_executable(10_runHW5MutiplicationExceptionTest multiplication_exception_test.cpp)
target_link_libraries(10_runHW5MutiplicationExceptionTest gtest gtest_main hw5_library)

