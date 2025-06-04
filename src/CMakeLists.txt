enable_testing()
add_subdirectory(lib)
add_executable(calculator main.c)
target_link_libraries(calculator lib)
add_test(t5 calculator car 5)

