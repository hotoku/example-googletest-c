add_executable(
  hello_test
  hello_test.cpp
)
target_link_libraries(
  hello_test
  GTest::gtest_main
)
target_link_libraries(
  hello_test
  add
)
add_test(NAME hello_test COMMAND hello_test)
