cmake_minimum_required(VERSION 3.10)

project(googletest-download NONE)

include(ExternalProject)
ExternalProject_Add(googletest
 URL https://github.com/google/googletest/archive/master.zip
 SOURCE_DIR        "/home/cezeri/Documents/WorkSpace/ci_cpp_project/tst/tst/googletest-src"
 BINARY_DIR        "/home/cezeri/Documents/WorkSpace/ci_cpp_project/tst/tst/googletest-build"
 CONFIGURE_COMMAND ""
 BUILD_COMMAND     ""
 INSTALL_COMMAND   ""
 TEST_COMMAND      ""
)
