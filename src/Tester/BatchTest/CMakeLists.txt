project(transaction-tester CXX)

file(GLOB SRC "*.cc" "**/*.cc")
add_executable(batch-test ${SRC})

target_link_libraries(batch-test transaction-tester transaction-tester-algorithm argument-parser)
