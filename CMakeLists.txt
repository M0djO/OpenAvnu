cmake_minimum_required (VERSION 2.8) 
project (open-avb)
enable_testing()
add_subdirectory("thirdparty/cpputest")
add_subdirectory("daemons/common/tests")
add_subdirectory("daemons/mrpd")