cmake_minimum_required(VERSION 3.10)
project("Basic Test")
find_package( OpenCV REQUIRED )
add_executable(BasicTest BasicTest.cpp)
target_link_libraries( BasicTest ${OpenCV_LIBS} )
