cmake_minimum_required(VERSION 2.8)
project( bgsub )
find_package( OpenCV REQUIRED )
add_executable( bgsub bgsub.cpp )
target_link_libraries( bgsub ${OpenCV_LIBS} )

