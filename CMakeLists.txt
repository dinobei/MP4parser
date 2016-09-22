project(mp4parser)
cmake_minimum_required(VERSION 2.8)


set(CMAKE_C_FLAGS "-std=c++11 -g -Wall -Werror")
#set(CMAKE_CXX_FLAGS "-std=c++11 -Wall -Werror -Wl,--as-needed")
include_directories(
			${videobox_SOURCE_DIR}/Include
			${videobox_SOURCE_DIR}/lib/include)
link_libraries(m)

# --> core files
set(
	mp4.c
	mp4parser.c
	stream.c
)

#install(TARGETS mp4parser DESTINATION bin)
