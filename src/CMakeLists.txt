cmake_minimum_required(VERSION 2.8)
project( bgsub )
find_package( OpenCV REQUIRED )
add_executable( bgsub bgsub.cpp )
target_link_libraries( bgsub ${OpenCV_LIBS} )

# utilities
install (TARGETS bgsub DESTINATION $ENV{PWD}/../bin )
add_custom_target(clean-all
  rm -rf CMakeFiles CMakeCache.txt *.cmake Makefile *.o
)

