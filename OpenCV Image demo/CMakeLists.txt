cmake_minimum_required(VERSION 2.8)
project( untitled4 )
find_package( OpenCV REQUIRED )
add_executable( untitled4 main.cpp )
target_link_libraries( untitled4 ${OpenCV_LIBS} )