cmake_minimum_required(VERSION 3.3)
project( atmd )

add_definitions( -D_CRT_SECURE_NO_WARNINGS )

add_subdirectory( extern )

set( SOURCES atmd.cpp graphics.cpp )

add_executable( atmd ${SOURCES} )
target_link_libraries( atmd PUBLIC sdl sdlmain opengl32.lib winmm.lib dxguid.lib )

