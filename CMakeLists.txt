cmake_minimum_required(VERSION 2.8)
project(timed_queue CXX)
set(TARGET timed_queue)


add_subdirectory(src)
add_subdirectory(tests/func_tests)
add_subdirectory(tests/load_tests)
add_subdirectory(tests/perf_tests)