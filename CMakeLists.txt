cmake_minimum_required(VERSION 3.0)

project( ManipulateImage )

find_package( OpenCV REQUIRED )

include_directories( ${OpenCV_INCLUDE_DIRS} )

add_executable( ManipulateImage ManipulateImage.cpp )

target_link_libraries( ManipulateImage ${OpenCV_LIBS} )
