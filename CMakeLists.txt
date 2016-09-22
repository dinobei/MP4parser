project(mp4parser)
cmake_minimum_required(VERSION 2.8)


set(CMAKE_C_FLAGS "-std=c11 -g ")
#set(CMAKE_CXX_FLAGS "-std=c++11 -Wall -Werror -Wl,--as-needed")
include_directories(. )
aux_source_directory(. DIR_SRCS)
add_executable(mp4parser ${DIR_SRCS})
target_link_libraries(mp4parser -lm)


#install(TARGETS mp4parser DESTINATION bin)
